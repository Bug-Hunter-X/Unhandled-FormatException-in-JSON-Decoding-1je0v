# Unhandled FormatException in Dart JSON Decoding

This repository demonstrates a common error in Dart applications involving JSON decoding and provides a solution.

The `bug.dart` file showcases code that fails to handle the `FormatException` that can be thrown by `jsonDecode` if the JSON data is invalid.  This can lead to unexpected crashes or application instability.

The `bugSolution.dart` file presents a more robust approach that specifically catches `FormatException` and provides appropriate error handling, making the application more resilient.