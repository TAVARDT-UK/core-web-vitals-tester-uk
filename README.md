# Core Web Vitals and Page Speed Performance Auditor

[![Core Web Vitals Auditor](https://img.shields.io/badge/TAVARDT-Core%20Web%20Vitals-5b3cf5.svg)](https://tools.tavardt.com/uk/core-web-vitals-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits TTFB latency, compression headers, render-blocking scripts, and Cumulative Layout Shift stability.

***

## Core Web Vitals Audit Capabilities

* **Server Response and TTFB Analysis**: Precise measurement of initial Time to First Byte latency and edge infrastructure responsiveness.
* **Render-Blocking Resource Inspection**: Detection of synchronous CSS stylesheets and JavaScript assets delaying initial rendering.
* **Visual Stability Audit (CLS)**: Verification of explicit image dimensions and lazy loading implementations to eliminate layout shifts.
* **HTTP Compression Verification**: Audits Brotli and Gzip payload compression configuration.
* **W3C Performance Health Score**: Quantitative 0 to 100 performance score with prioritized remediation guidance.

***

## Installation and Execution

Requires Python 3.8 or higher with no external dependencies required.

```bash
git clone https://github.com/TAVARDT-UK/core-web-vitals-tester-uk.git
cd core-web-vitals-tester-uk
python cwv_tester.py https://company.co.uk
```

To output results in structured JSON format:

```bash
python cwv_tester.py https://company.co.uk -json
```

***

## Web Performance and Speed Optimisation Advisory

For enterprise page speed architectures aligning with W3C Standards and UK Digital Performance Architecture, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
