# Debug Automated UI Tests

In this challenge, you have a set of automated UI tests that you're in charge of. Some tests are passing and some are failing. You need to debug the tests to find what the problems are and fix them so all tests pass!

## Quality Engineer

Quality Engineers often have to maintain tests, monitors, alerts, etc. for their team. It's not enough to just point at something and say "it's bad". Instead, you investigate, ask questions, explore, assess, etc., and can help provide solutions as well!

## Specs

* Application Under Test (AUT): [OrangeHRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
* The tests are in this folder, but you can run them by using the play/debug button on the test, or in the Terminal with:

```bash
npx playwright test tests/challenges/ch3
```

## Goals

* Fix all tests in `/ch3` and run them so you have a single report that shows all tests pass
* Be aware that just because a test passes or fails, doesn't mean it's doing it for the _right_ reasons
* Also, make sure what the test _says it tests_ is **actually** what it tests
