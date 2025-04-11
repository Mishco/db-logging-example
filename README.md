# Logging example with Databricks notebook

## Logging Setup Function 

This Python module provides a utility function to configure logging in applications or notebooks, with options for logging to both the console and a file. 

Features 

 * Configurable logging level.
 * Option to log messages to a file.
 * Customized log format.
 * Clears existing handlers before configuration to prevent duplicate outputs.

Function: `setup_logging` 

Parameters 

    level (optional): Specifies the logging level. Default is logging.INFO. You can use other levels like logging.DEBUG, logging.WARN, etc. 

    log_to_file (optional): Boolean flag to enable logging to a file. Default is False. 
     
    filename (optional): The name of the file where logs will be saved if log_to_file is True. Default is 'app.log'. 
     

Return 

     Returns a configured logger instance.
     
