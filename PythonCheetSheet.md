# Comments

Single line comments start with #. Multiple line comments can be started and ended with three sets of quotes.

    # This is a comment
    
    """
    This is a multi-line comment.
    What do you think?
    """

# Defining a Function

    def one():
      return 1
      
# User Input

You can get user input using the raw_input() function. If you use the input() function instead, then it will be interpreted (or evaluated) first. In most cases, for user input, you'll want to use raw_input(). You will probably also want to cast the input.

    first = str(raw_input("Enter your first name:"))
    print "Hello " + first

