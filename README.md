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

![image](https://github.com/inside/no-mangling-option/assets/107884/95169a9a-c05a-4bc0-865d-917c45b386b3)

# Expected Behavior

We should see object names like shown in the screenshot below which has been taken in dev mode:

![image](https://github.com/inside/no-mangling-option/assets/107884/9b528de1-d615-498d-b2ca-20253b4a156e)