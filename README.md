# # Travala token

An implementation of a NEO-5 AVA token - [Travala.com](https://travala.com)

## Usage

There are standard NEP-5 token smart contract and 4 optional operations for this token:

### Methods

#### totalSupply

	* Returns the total token supply deployed in the system.

#### name

	* Returns the token name.

#### symbol

	* Returns the token symbol.

#### decimals

	* Returns the number of decimals used by the token.

#### balanceOf

	* Returns the token balance of the `account`.

#### transfer

	* Will transfer an `amount` of tokens from the `from` account to the `to` account.

#### approve

	* Grant permission for another user to withdraw from the invocation account up to an amount of `value`

#### allowance

	* Return amount of token allowed to withdraw from an user

#### transferFrom

	* Will transfer an `amount` of tokens from the `from` account to the `to` account with right granted for `originator`

#### lock

	* Will lock for an `amount` of tokens from the `from` account to the `to` account in a period of `lockTime`

#### unlock

	* Will transfer locked tokens from the `from` account to the `to` account in if locked period passed

### Events

#### transfer

	* The “transfer” event is raised after a successful execution of the “transfer” method.

