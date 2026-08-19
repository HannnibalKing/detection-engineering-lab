# Detection Engineering Lab

A small rule-replay service for testing Sigma-inspired detections against deterministic event fixtures.

```bash
npm test
npm start
```

`POST /api/detect` accepts rules and events and returns alert matches. The interface is intentionally simple so Sigma YAML parsing, ATT&CK mappings, SIEM backends, false-positive tracking, and regression corpora can be added without changing the evaluation boundary.

Reference formats: [Sigma](https://sigmahq.io/docs/) and [MITRE ATT&CK](https://attack.mitre.org/).