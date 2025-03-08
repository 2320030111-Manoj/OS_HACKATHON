# Suggestions

## Development Suggestions

**For some tools very useful** during the development, see [Development Tools](../../appendix/development-tools.md) for details.

<mark style="color:red;">**You should expect to (always) run into bugs that you simply don't understand while working on this and subsequent projects.**</mark>&#x20;

* When you do, reread the appendix on debugging tools, which is filled with useful debugging tips that should help you to get back up to speed (see section [Debugging](../../getting-started/debug-and-test/debugging.md)).&#x20;
* Be sure to read the section on backtraces (see section [Backtraces](../../getting-started/debug-and-test/debugging.md#backtraces)), which will help you to get the most out of every kernel panic or assertion failure.

{% hint style="info" %}
**Tips**

We also suggest you **read the** [**Your Tasks**](your-tasks.md) **as well as the** [**FAQs**](faq.md) **carefully** -- perhaps multiple times. A lot of the confusion comes from not reading them carefully.
{% endhint %}

{% hint style="info" %}
**Tips**

**`make check` runs all tests.**&#x20;

If you are debugging one test, you can run just that test with `make tests/threads/<test_case>.result`. Read the [Testing](../../getting-started/debug-and-test/testing.md) part for more details.
{% endhint %}
