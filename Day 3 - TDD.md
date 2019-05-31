TDD

A bug is not a typo.

-> write better code, less bugs
Class Human
  def initiliaze(name, age)
  @name = name
  @age = age
end
end

human = Human.new("Harry", 16)

class counter
  def initialize(count)
    @count = count
  end
end

counter = new.Counter(16)
expect(counter.add).to eq(16)

-> helps with navigate code

-> break down the problem to understand the requirements

-> stops you over complicanting problem

-> test drive solution to code

-> security

ARRANGE, ACT, ASSERT

describe FileSystem do -> targets class
  it 'can add items to storage' do -> title / description of the test
    file_system = FileSystem.new -> initializes a instance of the thing
    file = File.new -> initializes a new file
    file_system.store(file) -> calls method on the thing
    expect(file_system.display_files).to include(file) -> shows you what it is expecting
  end
end

Attribute reader -> check it out this evening
