## Installation

Clone the repository:

```
git clone https://github.com/lokeshchoudhary-lc/todo-cli.git
```

Install the dependencies:

```
npm i
```

Install the package globally on your machine:

```
npm i -g
```

## Usage

1. To view the TODO list:

```
todo list
```

2. To add a TODO task:

```
todo add <task>
```

For example:

```
todo add "Make Dinner"
```

Use quotations when using spaces in the text otherwise quotations are not necessary.

3. Mark tasks as done:

```
todo mark-done
```

This will mark all tasks as done. To mark specific tasks as done by their indices, run:

```
todos mark-done -t 1 2
```

where `-t, --tasks` can take at least one value. Values are separated by spaces.
