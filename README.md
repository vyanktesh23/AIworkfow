# AIworkfow
# AI Workflow Peer Review Checklist

This repository contains resources and scripts for evaluating AI workflow deployments as part of peer review.

## Checklist

### Unit Tests
- API unit tests (`tests/test_api.py`)
- Model unit tests (`tests/test_model.py`)
- Logging unit tests (`tests/test_logging.py`)
- Single script to run all tests: `tests/run_tests.sh`

### Performance Monitoring
- Performance monitoring guidelines (`monitoring/performance_monitoring.md`)

### API Functionality
- Supports predictions for specific countries and all countries combined.

### Data Ingestion and Automation
- Automated data ingestion script (`data_ingestion/ingestion_script.py`)

### Model Evaluation
- Supports multiple model comparison.
- Uses EDA visualizations and baseline comparisons (not included here).

### Deployment
- Containerized with Docker (Dockerfile not included; add as needed).

---

## Running Tests

To run all unit tests:

```bash
cd tests
./run_tests.sh
