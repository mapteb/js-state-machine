# jquery-state-machine
A State Machine implementation using jQuery

The classic [turnstile example](https://en.wikipedia.org/wiki/Finite-state_machine) is used for this [demo](https://mapteb.github.io/jquery-state-machine/jqueryStateMachineDemo.html).

This demo uses the following state transitions:
`
	 defaultState -      coinEvent -> handleCoin() - coinSuccessEvent - coinSuccessState
	 defaultState -      coinEvent -> handleCoin() - coinErrorEvent   - coinErrorState
	 coinErrorState -    coinEvent -> handleCoin() - coinSuccessEvent - coinSuccessState
	 coinSuccessState -  pushEvent -> handlePush() - pushSuccessEvent - pushSuccessState
`

If you like this project it would help if you could add a GitHub star at the top of this page.

