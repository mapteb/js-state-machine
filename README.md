# js-state-machine
A JavaScript State Machine implementation using jQuery

The classic [turnstile example](https://en.wikipedia.org/wiki/Finite-state_machine) is used for this [demo](https://mapteb.github.io/js-state-machine/jqueryStateMachineDemo.html).

This demo uses the following state transitions:<br />
<br />
`    defaultState     -  coinEvent -> handleCoin() - coinSuccessEvent - coinSuccessState`<br />
`    defaultState     -  coinEvent -> handleCoin() - coinErrorEvent   - coinErrorState`<br />
`    coinErrorState   -  coinEvent -> handleCoin() - coinSuccessEvent - coinSuccessState`<br />
`    coinSuccessState -  pushEvent -> handlePush() - pushSuccessEvent - pushSuccessState`<br />

If you like this project it would help if you could add a GitHub star at the top of this page.

