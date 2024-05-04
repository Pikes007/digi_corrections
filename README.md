# digi_corrections

Technical Assessment: Digicert

github actions workflow:

- has workflow_dispatch event trigger for manual run workflow
- within workflow star wars app dependencies are installed, built and started 
- next test repo (Pikes007/sw_requirements) is cloned and python installed
- install test dependencies using: pip install -r requirements.txt
- run test suite using: pytest -v -s against the app under test
- post job cleanup
