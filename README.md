# js-state-machine

A JavaScript State Machine implementation using jQuery

The classic [turnstile example](https://en.wikipedia.org/wiki/Finite-state_machine) is used for this [demo](https://mapteb.github.io/js-state-machine/jqueryStateMachineDemo.html).

This demo uses the following state transitions:
| Initial State | Pre-Event | Process | Post-Event | Final State |
| --- | --- | --- | --- | --- |
| defaultState -> | coinEvent -> | handleCoin() -> | coinSuccessEvent -> | coinSuccessState |
| defaultState -> | coinEvent -> | handleCoin() -> | coinErrorEvent -> | coinErrorState |
| coinErrorState -> | coinEvent -> | handleCoin() -> | coinSuccessEvent -> | coinSuccessState |
| coinSuccessState -> | pushEvent -> | handlePush() -> | pushSuccessEvent -> |pushSuccessState |

More information on this project is at:
<https://dzone.com/articles/a-simple-javascript-state-machine>

If you like this project it would help if you could add a GitHub star at the top of this page.

An extension of this project to include server models is [js-state-machine-v2](https://github.com/mapteb/js-state-machine-v2)
