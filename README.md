# Testing Relationships Between Classes

## Quickstart

Clone, then:

```bash
$ bundle install
$ rspec
# You should see four pending tests
```

## Instructions

Fill in the four tests in `spec/secret_diary_spec.rb`.

Don't:

* Change `secret_diary.rb`
* Add any new files
* Create any new classes

Do:

* Use `double` — [Reference docs here](https://relishapp.com/rspec/rspec-mocks/v/3-5/docs/basics/test-doubles)
* Use `expect(...).to receive(...)` [Reference docs here](https://relishapp.com/rspec/rspec-mocks/v/3-5/docs/basics/expecting-messages)

## Check your work

Remove lines 23 (`@diary.read`) and 28 (`@diary.write(new_message)`) from lib/secret_diary.rb.

Does SecretDiary still do what it's supposed to do?

Do your tests still pass or do they fail?

If your tests still pass, is there any way to write them which means they will fail if SecretDiary is broken in this way?
