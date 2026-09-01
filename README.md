# Universal Dragon Eye

Universal Dragon Eye is currently a **static safety-monitoring dashboard and service concept page**.

## Current implementation

The default branch provides a browser interface with presentation cards for:

- fire and smoke alerts
- motion alerts
- shop or room safety
- weather risk
- worker safety
- emergency status
- setup and maintenance information
- contact/demo information

## Current boundary

This repository does **not** currently include:

- camera capture or streaming
- OpenCV or model inference
- fire, smoke, face, motion, or object-detection code
- alert delivery services
- a backend API
- live Raspberry Pi or CCTV integration

The visible alert values are UI/demo content. They must not be treated as real safety detections.

## Run locally

~~~bash
python3 -m http.server 8080
~~~

Then open http://localhost:8080.

## Before real deployment

A production safety system still needs an authenticated backend, tested detection models, camera permission handling, audit logs, alert delivery, failure monitoring, and human verification. It must not be used as the sole life-safety control.
