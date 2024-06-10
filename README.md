# ETH_Beginner_project: Create a Token

// SPDX-License-Identifier: MIT <br>
pragma solidity 0.8.18;<br>

/\*<br>
REQUIREMENTS<br>

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)<br>
2. Your contract will have a mapping of addresses to balances (address => uint)<br>
3. You will have a mint function that takes two parameters: an address and a value.
   The function then increases the total supply by that number and increases the balance of the “sender” address by that amount<br>
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens.
   It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the “sender”.<br>
5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.<br>
   \*/<br>

contract MyToken {

            // public variables here
            
            // mapping variable here
            
            // mint function
            
            // burn function
}
