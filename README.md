# test-http — Official Wyn Package

HTTP test helpers for API testing. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/test-http
```

## Usage

```wyn
var resp = Http.get("http://localhost:8080/api/health")
assert_contains(resp, "ok")
assert_json_has(resp, "status")
```
