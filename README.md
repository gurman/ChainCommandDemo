# ChainCommandDemo
App for commands chaining demonstration. You can make chains from commands. Each chain consists of one main command
and set of member commands. Execution of main command will execute also all it's member commands. Also you cannot execute
member command without whole chain.

Installation
------------

```bash
 composer install
```

Usage
======
```bash
bin/console foo:hello
bin/console bar:hi
```
Also possible to comment or modify `chain_command` section in `config/services.yaml`

Used bundles
============
https://github.com/gurman/ChainCommandBundle

https://github.com/gurman/FooBundle

https://github.com/gurman/BarBundle
