# ROT13 Decoder

The ROT13 Decoder is a simple JavaScript function that decodes strings encoded using the ROT13 cipher. ROT13 (rotate by 13 places) is a type of substitution cipher where each letter in the alphabet is shifted 13 positions.

## Usage

The `rot13` function takes a ROT13 encoded string as input and returns the decoded string. It preserves the case of the letters and does not transform any non-alphabetic characters such as spaces or punctuation.

To use the ROT13 Decoder, follow these steps:

1. Include the `rot13` function in your JavaScript project or file.

2. Call the `rot13` function and pass the ROT13 encoded string as an argument.

   ```javascript
   var encodedString = "SERR PBQR PNZC";
   var decodedString = rot13(encodedString);


3. The function will return the decoded string. You can then use or display the decoded string as needed.

    ```javascript
    console.log(decodedString); // Output: "FREE CODE CAMP"

## Example
    Here's an example that demonstrates the usage of the ROT13 Decoder function:

         ```javascript
        var encodedString = "SERR PBQR PNZC";
        var decodedString = rot13(encodedString);
        console.log(decodedString); // Output: "FREE CODE CAMP"


## Limitations
The ROT13 Decoder function only works for ROT13 encoded strings that contain uppercase letters. It does not support decoding of strings with lowercase letters or non-alphabetic characters.

## License
This project is licensed under the MIT License.

 ```javascript
Feel free to modify or enhance the README.md file as per your requirements.






