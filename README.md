# Unexpected Behavior with Read-Only Getter Method in Ruby
This example demonstrates unexpected behavior when trying to modify a value through a getter method intended to be read-only in Ruby.  The getter method does not modify the underlying instance variable, showcasing potential confusion when one might expect setter-like behavior. This is not inherently a 'bug' but rather unexpected behavior in Ruby's approach to getter methods.

The `bug.rb` file showcases the issue.  The `bugSolution.rb` offers a solution.