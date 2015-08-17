# FAAS

Propose remote functions as a services. Use remote services like simple calls a local functions in your code.

# Examples

Faas::call( 'dobryakov/stupid-calculator', { 'a' => 2, 'b' => 3 } ) # -> 5

Faas::call( 'dobryakov/validates-email', { 'email' => 'test@somedomain.com' } ) # -> true

# Under the hood

It's make a HTTP-request (synchronous for PHP, asynchronous for JS, for example) to your or somebody remote endpoint with wrapped data, and unwrap the answer to your inline code.

# TODO

Callbacks
Exceptions
Tests
