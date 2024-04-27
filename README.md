# Features
. Single IP and IP range scanning

. Multi-threaded scanning for faster results

. Support for proxy usage

. Save results to files

# Usage

1. Clone the repository:



2. Install the required dependencies:

pip install -r requirements.txt



3. Install the required dependencies:

pip install -r requirements.txt


4. Run the tool:

python scan.py [IP_INPUT] [OPTIONS]
Replace [IP_INPUT] with the target IP address or range. Additional options can be specified:

-t, --threads: Number of threads to use (default is 10)
-p, --port: Port to scan (default is 80)
-P, --proxy: Proxy IP and port (e.g., 12.34.56.6:80)
-o, --output: Save output to a file
-f, --file: Read IP addresses from a file


# Examples

# . Scan a single IP:

`python cdnscanner.py 192.168.1.1`

