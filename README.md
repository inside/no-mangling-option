# Installation

1. Clone this repo
2. `npm install`
3. `npm run build -- --profile --no-mangling`
4. `npm start`

# Steps to reproduce

1. Open your browser to `http://localhost:3000`
2. Open the devtools
3. If installed, go to the React Developer Tools profiler tab
4. Click on "Reload and start profiling"
5. After a few seconds, click stop on the red circle
6. A flamegraph with mangled names appears like shown in the screenshot below:

![image](https://github.com/inside/no-mangling-option/assets/107884/0233417f-875e-43f9-b7aa-546adb847ae5)

# Expected Behavior

We should see object names like shown in the screenshot below which has been taken in dev mode:

![image](https://github.com/inside/no-mangling-option/assets/107884/ed372007-9a13-4327-8377-12b05f1efc2f)
