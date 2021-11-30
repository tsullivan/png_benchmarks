# png_benchmarks

Test setup for benchmarking Dashboard PNG performance.

Benchmark comparisons include the number of panels in the dashboard.

## Usage
```
cd analyze
yarn
node main.js -f ../share/default-tests-kibana.log
```

1. Run the script commands above
2. Copy and paste the script output into Dev Tools.
3. Import `performance_dashboard.ndjson` into Kibana v8.1.0-SNAPSHOT

![image](https://user-images.githubusercontent.com/908371/144098447-fbeb8471-4b77-4cf7-88ee-a93cb4c02b48.png)

