static typed languages - languages like java that check for type
errors during the compile stage. If there is a type error the compile
stage will not complete until the type error is corrected.

static languages need to have their data type defined. E.g if writing an
variable with the value 5, you will need to declare it as an int first.

int num
num = 5

Dynamically typed languages - languages like javascript check for their
type errors during runtime. The programme can finish compiling even if there
is a type error.

You don't have to declare what type of data type something is which can cause
problems down the line. If you set a variable then tried to reset it's value
but a typo occurred a new variable would then be created.

E.g
num = 5
numb = num + 5

The intention was to change num to 5 + 5 but instead a new variable was created.
