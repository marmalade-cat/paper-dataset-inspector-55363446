Paper Dataset Inspector

A minimal in-browser prototype that fetches a paper page or PDF URL, finds links to machine-readable dataset files (CSV, TSV, JSON, ZIP), retrieves HTTP headers and small samples, and shows a short report. Uses only browser fetch; CORS may prevent inspecting some remote hosts. No server or dependencies.

Usage: open index.html in a modern browser, paste a URL (HTML page or direct PDF), click Inspect.

Limitations: CORS restrictions, no PDF text parsing beyond searching for link-like patterns inside fetched PDF bytes, simple heuristics for file detection, samples limited to first few KB.

License: Public domain for this prototype.
