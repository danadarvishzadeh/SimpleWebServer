# SimpleWebServer
Simple Multithreaded HTTPServer Implemented in Python

This is a personal project written in Python. I will share my designs and implementation plans for this project actively in this README file.

### Here are description of what needs to be done for this implementation
- A somewhat simple interpretation of HTTP protocol needs to be used. It will be implemented in a HTTPHandler class that only handle HTTP related functionalities. Worker clss will inherit from this class.
- A Worker class is needed for listening on configured ports and recieving incoming data.
- A Configuration class is needed for parsing configuration files.
- A Parser class to be used as one of the parents of Configuration class.
