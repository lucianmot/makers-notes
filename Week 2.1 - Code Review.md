# Code Review #

-> Reviewing someone else's code

## Why ##
Reviewer(A)                                  Reviewee(B)
* Seeing different ways of doing something(both A & B)
   -> not just one way
* Feedback on how readable your code is(B)
* Learn to read/review code(A & B)
* Quality code(B)

## Companies use of Code Review ##
* Two pair of eyes on the code
* Gateway to production code

Convention
  Style guide
  * 2 space indendation
  * classes are CamelCase
  * variables are snake_case
  * method that return a boolean end with ? 
  
You can write all your test with just 2 rspec matchers
* expect().to eq
* expect().to raise_errors
You can still use respond_to as scaffolding  until you finish writing your tests, but they become redundant at the end.

Use github for code review, find your partner pull request in the original repo airport. Start a review.

## Code Review Exercise ##
* Where to start?
  -> 1st file
  -> 1st commit

Actual proper way
Gemfile
1. READEME.md -> approach
              -> goal
              -> diagramme
2. Airport_spec.rb
   Plane_spec.rb -> These test for all user stories
                 -> run tests
3. Airport -> readable -> Don't understand?
   Plane -> DRY
         -> Long? / Complex

## Week Kick Off ##
Week 2 Goals

Object Oriented -> classes
                -> unit tests
                -> principles : delegation
                                encapsulation
                                inheritance
                                cohesion / SRP
                                polymorphism
                focus on WHY? (Why do these 2 things work like this togheter?)
TDD -> mocking/isolation testing (find out more about mocking this week)
    -> coverage test
Review
Week 1 skills -> Pairing
