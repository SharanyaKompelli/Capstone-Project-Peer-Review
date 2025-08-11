Are there unit tests for the API?	Yes	Basic endpoint tests exist
Are there unit tests for the model?	No	No direct tests for model predictions
Are there unit tests for the logging?	No	Logging is not validated in tests
Can all of the unit tests be run with a single script and do all of the unit tests pass?	Yes	pytest runs all tests successfully
Is there a mechanism to monitor performance?	No	No performance dashboard or monitoring
Was there an attempt to isolate the read/write unit tests from production models and logs?	Yes	Test config uses mock data
Does the API work as expected? (specific country & all countries combined)	Yes	Returns predictions for both specific and all countries
Does the data ingestion exist as a function or script to facilitate automation?	Yes	Script in ingest.py
Were multiple models compared?	No	Only one final model tested
Did the EDA investigation use visualizations?	Yes	Multiple charts and plots used
Is everything containerized within a working Docker image?	Yes	Dockerfile builds successfully
Did they use a visualization to compare their model to the baseline model?	No	Only textual comparison provided
