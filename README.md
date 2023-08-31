# Pi-Memory-Alert
This example shows you you can configure a generic sensor component as a module in Viam that will alert through Twilio in the event of a condition being met.

# Project Structure
The definition of the new resources are in the main file of the src directory.

The exec.sh script is the entrypoint for a module and calls the main.py file. The main.py file contains the definition of a new sensor model and code to register it.

# Configuring and using the module
Twilio module for alerting based on a do_command(). Intended to be implemented as a Viam module. Requires the following in the config: ['auth_token'] ['account_sid'] ['recipient_phone'] ['deliverer_phone'] ['threshold']
