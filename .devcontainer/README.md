There is a set of build containers that can be used to compile the code with a specific compiler stack.
The options are:

stillwater/universal:gcc9builder
stillwater/universal:gcc10builder
stillwater/universal:gcc11builder
stillwater/universal:gcc12builder
stillwater/universal:clang11builder
stillwater/universal:clang12builder
stillwater/universal:clang13builder
stillwater/universal:clang14builder

Simply reference the desired container in the devcontainer.json and that specific build environment will be selected by VSCode.
