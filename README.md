# storyshots-super-expression-failure
Filing an issue with storybook. Storyshot tests are failing with an ambiguous error message.

## Steps to reproduce
1. Clone the repository: `git clone https://github.com/kmurgic/storyshots-super-expression-failure.git`
1. Install dependencies`npm i`
1. Run storybook and see that it is working as expected `npm run storybook`
1. Run storyshot tests `npm test`

### Expected
The tests run without issue 🥳

### Actual
The tests fail with the error message `TypeError: Super expression must either be null or a function`
