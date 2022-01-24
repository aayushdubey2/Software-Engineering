<details>
<summary>NgRX</summary>

- NgRx is a framework for building reactive applications in Angular.
- Inspired by Redux pattern.
- Used for state management in angular projects.

</details>

<details>
<summary>Redux</summary>
Redux is a pattern and library for managing and updating application state, using events called "actions".
</details>

<details>
<summary>How Redux pattern works in Angular?</summary>

- Component dispactes an action. (Button click)
- Reducer takes that action and fetch the old state from store and create a new state out of it. 
- This new state is added in store. 
- Whenever a new state is added, component is notified using a selector. 

</details>

<details>
<summary>Why use NgRX?</summary>

- Without NGRX we can also do this, using services. But when project grows bigger we have a lot of service. Instead of having many services we can have a centralized store to manage the state.

- Also instead of making repetative HTTP calls to a server to the fetch same data (a common scenario), this data can be stored in the store and can be retrieved from there whenever needed. 
</details>