Amplifying your Web App with Native Code
========================================

Portable Native Client (PNaCl) and Emscripten compile C/C++ code for use as
part of the client side of your Web App. Because these technologies leverage
the security guarantees of the NaCl sandbox and Javascript respectively, they
don’t require plugin installation or a user opt-in. This unlocks a 30+ year
treasure trove of C/C++ libraries and applications for use on the Web.
Additionally, since scripting languages like Python, Lua, Ruby, Tcl/Tk, and
Bash are implemented in C, the large body of code available in these languages
can also be integrated seamlessly into your app.

Learn how you can:
  * Develop Web Apps in the language you prefer.
  * Reuse the 200+ libraries and applications ported to Native Client.
  * Develop in your browser, including source control, editing, compilation,
    and debugging.
  * Move code off your server into the browser, for speed and security.
  * Maximize the performance of your application with native code.


View slides online [here](https://flagxor.github.io/fluent-2015).

Clone sample Python App [here](https://github.com/flagxor/fluent-pnacl-sample).

NOTE: This slide deck uses submodules.
Before use, run: git submodule update --init.

To host slides locally:
  python -m SimpleHTTPServer 1688

Then view: http://localhost:1688/
