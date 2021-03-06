# HealthCare HL7 XML

Please, go through the following steps if you want to contribute to this project:

1. Report an issue. Describe it as much as you can, including how to reproduce it if possible.
2. Fork the repository, create a new branch
3. Develop your changes, make sure all unittests are still working. Add new unittests if needed.
4. Create a pull request

## Environment
Use the provided Docker container environment to develop your changes.

This environment includes:
* IRIS For Health (Community)
* Installer
* UnitTests

To start up you development environment:
```console
docker-compose build
docker-compose up
```