# FAAS

Propose remote functions as a services. Use remote services like simple calls a local functions in your code.

# Examples

Faas::call( 'dobryakov/stupid-calculator', { 'a' => 2, 'b' => '3' } ) # -> 5

Faas::call( 'dobryakov/validates-email', { 'email' => 'test@somedomain.com' } ) # -> true

