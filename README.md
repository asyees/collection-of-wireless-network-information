# collection-of-wireless-network-information

Executes commands through the command line using subprocess.call() to retrieve wireless network profiles and export them to an XML file.
There should be a pause of 2 seconds to allow time for command line operations to complete.
Parses an XML file with information about wireless network profiles.
Defines the info_pc() function, which collects PC information such as network name, processor, system, and IP address.
Defines the get_ip() function, which obtains the external IP address of the PC.
Defines a wifi() function that retrieves the wireless network name and password from an XML file.
Defines the all_info() function, which aggregates all collected data.
Defines a send_mail() function that sends an email with the collected information to the specified address.
Defines a main() function that calls all of the above functions.
Calls the main() function to start the program.
In general, this code collects information about the PC and the wireless network and then sends this information via email.
