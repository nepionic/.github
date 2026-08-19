# Nepionic

Welcome to **Nepionic**, an open-source engineering ecosystem dedicated to **Beckhoff TwinCAT** libraries and industrial automation tooling. We bridge the gap between traditional Operational Technology (OT) and modern Information Technology (IT) paradigms.

---

## 🛠️ Focus Areas

### 1. TwinCAT & PLC Libraries
Our primary PLC infrastructure is **mostly written in IEC 61131-3 Structured Text (ST)**. We focus on modular, object-oriented, and reusable industrial code architectures.
* **[Mc_MoveContinuousVelocity](https://github.com/nepionic/Mc_MoveContinuousVelocity)**: Advanced continuous velocity profile extensions.

### 2. Automation Tooling & DevOps
We build companion software, code generation utilities, and deployment pipelines using modern software engineering languages (**Go, Rust, Python, Java, C#**):
* **[ADS Logger](https://github.com/nepionic/ads-logger)**: ADS Logger is a Go library for subscribing to TwinCAT ADS log messages and streaming decoded entries over a channel. Also includes a standalone dump tool.
* **[TwinCAT Analytics Go](https://github.com/nepionic/twincat-analytics-go)**: TwinCAT Analytics library for decoding binary MQTT messages.
* **[TwinCAT Analytics Redpanda Connect Plugin](https://github.com/nepionic/twincat-analytics-redpanda-connect-plugin)**: TwinCAT Analytics connector for Redpanda. Reads from binary MQTT streams and puts the data into topics.
* **[TwinCAT Kuma](https://github.com/nepionic/twincat-kuma)**: Tool to send uptime signals to [Uptime Kuma](https://github.com/louislam/uptime-kuma).
* **[TwinCAT Scope View for Julia](https://github.com/nepionic/TcScopeView.jl)**: A Julia package for reading TwinCAT 3 Scope View .svb binary recording files.
* **[TwinCAT Scope View for Python](https://github.com/nepionic/python-tcscopeview)**: Python reader for TwinCAT 3 Scope View .svb binary recording files.
* **[Magician](https://github.com/nepionic/magician)**: RESTful API for Automation Interface written as a C# Visual Studio extension. Particularly suited for AI workflows. Includes starting Claude skill.
* **[OpenTelemetry Collector](https://github.com/nepionic/otel-collector)**: Custom OpenTelemetry Collector distribution that bridges Beckhoff TwinCAT ADS telemetry to any OTLP-compatible backend.


---

## 🚀 Getting Started

To use our TwinCAT libraries, choose one of the following methods:

1. **Direct Download**: Clone the specific repository and add the library target inside your TwinCAT XAE (eXtended Automation Engineering) environment.
2. **Package Management**: Pull targeted modules through our upcoming library descriptor infrastructure.

```bash
# Clone a core repository
git clone https://github.com/nepionic/<repo>
```

---

## 🤝 Contributing

We welcome contributions from the industrial automation community! 
* Feel free to open an **Issue** if you spot a bug or want to request an IEC 61131-3 library feature.
* **Pull Requests** targeting code optimisation, bug fixes, or documentation enhancements are highly encouraged.
* Ensure code styles align with standard Object-Oriented PLC (OOPLC) patterns in TwinCAT.

---

## 📄 License

Unless stated otherwise within a repository, Nepionic projects are licensed under the **MIT License**. Check individual repository roots for explicit license files.
