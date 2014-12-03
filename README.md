webserv
=======

A web server which processes client HTTP GET requests via sockets for web pages or cgi scripts hosted on the server machine.

The source code has been deleted as instructed by Boston University Computer Science Department.
================================================
Assignment 3
================================================

Team member: Jingzhi Gao, Tianyou Luo


=========================================================================
Make file commands:
    
     "make all" makes everything
    
     And then everything else is just "make <part name>" e.g. make webserv
    
     make clean cleans everything up
=========================================================================


=========================================================================================
Usage:
     To run the web server type:
     $./webserv port-number

     To use a web browser as a client and make request to the webserver:
     http://ip.address.of.server:port-number/request

     To execute a script on the server, use:
     http://ip.address.of.server:port-number/request.cgi

     most test files can be accessed directly from index.html on the server

     To use my-historagm:
     http://ip.address.of.server:port-number/gnuplot.cgi?file=filename&pattern1=pattern1&...

     A non-existent request corresponds to an HTTP error status code of 404
===========================================================================================


=========================
Advanced Features:
    
     Web cache and server configuration
=========================
