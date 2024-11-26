### 1. Solidity version should be specific, not wide

- `pragma solidity ^0.8.13;`
- should be `pragma solidity 0.8.13;` or some newer version



### 2. no initial deposit? 

- if there is no initial deposit, how will we pay to first winner?

- there is no receive function, so we can't send ether to the contract if we will out of funds

- if someone wins, when balance of contract is 2, we again don't have enough ether to pay to the next winner

```diff

```

### 3. So much magic numbers


### 4. There is no withdraw function

- we should have a withdraw function so that owner can withdraw funds

### 5. No owner

- we should have an owner and only owner should be able to call certain functions (withdraw)
