# deninject-issue-1-sandbox

Sandbox project to have a common ground in order to try to fix issue#1 for "deninject" ==> https://github.com/brmcerqueira/deninject/issues/1

## Side usefull links

https://deno.land/manual@v1.35.0/advanced/typescript/configuration

How to run it
* `deno run -A --config ./deno.jsonc main.ts`
<pre>
Unsupported compiler options in "file:///Users/obioscaa/Documents/_Curro/_T2C/_PoC/deninject-issue-1-sandbox/deno.jsonc".
  The following options were ignored:
    experimentalDecorators
error: Uncaught Error: Bind not found for 'ClassB'.
            throw new BindError(identity, token);
                  ^
    at Injector.privateGet (https://deno.land/x/deninject@1.0.5/injector.ts:248:19)
    at Injector.get (https://deno.land/x/deninject@1.0.5/injector.ts:220:21)
    at file:///Users/obioscaa/Documents/_Curro/_T2C/_PoC/deninject-issue-1-sandbox/main.ts:28:20
</pre>

## deno --version
<pre>
deno 1.34.3 (release, x86_64-apple-darwin)
v8 11.5.150.2
typescript 5.0.4
</pre>