# turbo-octo-tribble
Using javascript to parse any URL 

Use Javascript to parse a URL address entered into a textbox into its component parts (protocol, port, domain and subdomain, path, and a list of parameters – both parameter name and values). The URL entered should be displayed as a clickable link (use the (<a> tag, and href attribute, though you may need to add information if the URL is not already well-formed.) (Use the Javascript to create the table. You will probably want to create helper methods such as writeCell (an individual data item preceded by <td> and followed by </td>), writeRow (write several cells based on the passed arguments – preceded by <tr> and followed by </tr>). For example, if the following URL is typed into the textbox

http://venus.cs.qc.cuny.edu/~lteitelman/cs355/myPage.html?name=Lawrence&title=instructor&building=Kiely

The table might look something like this:

Description	Entry	Additional Information	Source
Protocol	http	HyperText Transfer Protocol	Provided
Port	80		Default
Full Address	venus.cs.qc.cuny.edu	Corresponding IP address
(extra credit)	Lookup
Top-Level Domain	edu		Provided
Domain Name	cuny.edu		Provided
Subdomain Name	venus.cs.qc		Provided
Path	~lteitelman/cs355/connected.php		Provided
Parameter #1	name	Value is “Lawrence”	Provided
Parameter #2	title	Value is “instructor”	Provided
Parameter #3	building	Value is “Kiely”	Provided

You should be mindful or URLs that do not include all components (keep in mind that the number of segments in a domain must be at least 2 but arbitrary large, while the number of parameters can be 0 or arbitrarily large.) The code should make assumptions about reasonable defaults where appropriate (http where no protocol is provided, and the default port that usually goes with a protocol when the port itself is unspecified). Issue a meaningful error when the URL is so poorly formed that it cannot be parsed. 

