# Identicon

**Demo Application to learn how to deal with Elixir lang.**

#### Running

In order to run this Application You need Elixir SDK and Erlang SDK provided on Your machine.

After You downloaded the SDKs You have to follow the instructions (https://www.rebar3.org/docs/getting-started) to install rebar3 on Your machine.
(On Windows simply download the binary and paste it to erl_home/bin)

Now You are ready to use this Application.
Simply clone this repository, navigate in Your console to the the root of this project and open the interactive Elixir console:

```bash
iex -S mix
```

Then You can call the main function of the Identicon module with Your input:

```bash
Identicon.main("My fancy input")
```

In the project root appears a file named `My fancy input.png`

That is Your identicon!

Have fun!