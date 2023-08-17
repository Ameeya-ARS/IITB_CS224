# IITB_CS224
• Implemented Peer to Peer network for searching and downloading files on a network of clients.
• Each client setups TCP connections with its immediate neighbours only.(unique ID of client, port for accepting connections, neighbours and files to be downloaded are given via config file).
• Each of the client searches for files and downloads the file from neighbour with least unique ID.
• MD5 hash of the downloaded files is calculated and reported for verification of downloaded files.
