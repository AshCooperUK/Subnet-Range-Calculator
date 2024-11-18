https://html-preview.github.io/?url=https://raw.githubusercontent.com/AshCooperUK/Subnet-Range-Calculator/refs/heads/main/subnetcalc-v2-16112024.html

This script is a Subnet Range Calculator that provides an interactive tool for managing and calculating subnet configurations. 

Here's a summary of its functionality:

IP Address Validation and Range Calculation:

Allows users to input an IP address and select a subnet mask.
Validates the provided IP address.
Calculates the network address, broadcast address, usable IP range, and the number of usable clients based on the subnet mask.
Subnet Management:

Users can add multiple subnets, ensuring no overlap between existing subnets.
Tracks all added subnets and provides details such as:
Subnet Mask (in dotted decimal format).
Network Address.
Broadcast Address.
Range of usable IP addresses.
Number of usable clients.
Conflict Detection:

Ensures that newly added subnets do not overlap with any existing subnets.
Dynamic Subnet Mask Options:

Provides a dropdown list of subnet masks ranging from /8 to /30, dynamically updating possible ranges based on the input IP address.
Total Clients Calculation:

Keeps a cumulative count of usable clients across all added subnets.
Exporting and Printing Configurations:

Offers options to:
Print the network configurations.
Export the configurations into a .doc file for documentation purposes.
User Interface Features:

Includes buttons for actions such as updating ranges, adding subnets, and removing the last added subnet.
Displays error messages for invalid inputs or overlapping subnets.
Provides a print-friendly interface.
The script is implemented in HTML and JavaScript, with a focus on ease of use and clear feedback for network planning and design.
