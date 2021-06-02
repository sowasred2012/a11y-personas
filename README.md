# Accessibility Persona Testing

## Why?

- We should be mindful of accessibility at all times; an accessible website is better for _everyone_.
- External accessibility checks are infrequent, and come with a cost.
- As developers, we interact with and consume the projects we build from the point of view of our own abilities. It's not always easy to consider how a web page might be experienced by users with different abilities.
- If the setup instructions are simplified enough, we could run tests with everyone on the team, or even the company, and at regular intervals.

## Shortcomings

- Persona testing is not a substitute for real world user testing.
- Differently abled users will use a plethora of assistive technology that Chrome and the various extensions mentioned here simply are not a substitute for.

## Setup

### Extensions

Each persona uses a different set of Chrome extensions to simulate certain conditions, this is what each of them do:

| Extension            | Description                                                 |
| -------------------- | ----------------------------------------------------------- |
| Chrome Sound Effects | Adds distracting sounds to actions performed in the browser |
| ClaroRead            | Allows highlighted speech to be read aloud                  |
| Clever Mute          | Disables all website audio                                  |
| Hands Free for Web   | Allows you to control your browser with your voice          |
| High Contrast        | Applies a high contrast filter to all websites              |
| Midnight Lizard      | Applies a dark colour scheme to all websites                |
| OpenDyslexicFont     | Applies a dyslexia friendly font to all websites            |
| Screen Reader        | A browser based screen reader                               |
| Stylus               | Allows custom stylesheets to be applied to all websites     |
| Tampermonkey         | Allows custom JS scripts to be applied to all websites      |

### Pre-requisites

You just need Chrome. Chromium on Ubuntu seems to not be packaged with the voices required for the screen reader extension, so go for the [full fat Chrome](https://www.google.com/chrome/) if you don't have it already.

### Personas

- For each persona you'll be working with, create a new profile in Chrome.
- Follow the setup instructions for the persona you'll be working with:
  - [Ashleigh](personas/ashleigh.md)
  - [Chris](personas/chris.md)
  - [Claudia](personas/claudia.md)
  - [Pawel](personas/pawel.md)
  - [Ron](personas/ron.md)
  - [Saleem](personas/saleem.md)
  - [Simone](personas/simone.md)

## References

This repo and the documentation within is a condensed version of information the GOV.UK accessibility team has put out on their blog, all relating to accessibility persona testing:

- [Remote accessibility persona testing][1]
- [Using personas to test accessibility][2]
- [Setting up personas][3]

[1]: https://accessibility.blog.gov.uk/2021/03/30/remote-accessibility-persona-testing/
[2]: https://accessibility.blog.gov.uk/2019/02/11/using-persona-profiles-to-test-accessibility/
[3]: https://alphagov.github.io/accessibility-personas/setup/#setting-up-personas
