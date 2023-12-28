# End-to-End Testing with Playwright

The purpose of this repository is to provide a comprehensive guide on initiating end-to-end testing for dev.ema.co using the Playwright testing framework.

## Setup

**Install Playwright Python:**

	pip3 install playwright
 
**Install Playwright Globally:**

	npm install -g playwright

**Verify Installation:**

	playwright --version

**Install the required browsers:**
 
	playwright install


## How to run end-to-end tests for ema-dev?

1. Clone the repository to your local machine.
2. Open `config.json` and input your credentials.
3. Create a new Python class for your test, using `sampleChatTest.py` as a reference.
4. Run `playwright codegen` in the terminal to generate code for your end-to-end test.
5. In `main.py`, instantiate an object of your test class and execute the test.
6. Before running `main.py`, update the oktaSignInCode in `config.json` with the latest code.
7. Execute `main.py` to run your test and ensure everything works as expected.
8. Happy Coding!

## References

https://playwright.dev/python/docs/intro

https://playwright.dev/python/docs/codegen-intro

https://www.youtube.com/watch?v=oPjfDkge8Vc&ab_channel=JohnWatsonRooney
