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

#. Scan a single IP:

`python cdnscanner.py 192.168.1.1`

#. Scan an IP range:

`python cdnscanner.py 192.168.1.0/24`

#. Scan using a proxy:

`python cdnscanner.py 192.168.1.1 -P 12.34.56.6:80`


#. لفحص ip range ورأيت فرعيات عنوان ال ip

`python3 scan.py 15.197.142.0/24`


#. لفحص عنوان ال ip عبر port محدد

`python3 scan.py 15.197.142.0/24 -p 80 -t 100`


#. لفحص عدة ip من ملف واحد موجود لديك عبر بروكسي

`python3 ping.py -f cloudflare.txt -p 80 -P 89.221.224.92:80 -t 100`

#. ملاحضه تستطيع الفحص بدون اي أتصالا ب الانترنت
# Scan front a flaer:

. scan cloudflaer🌚👇

`python scan.py -f rang_cloudflaer.txt`

scan cloudfront🌚👇
`python scan.py -f rang_cloudfront_txt`


# Output

#. The tool generates two output files:

`cloudflare_cloudfront_results.txt`: Contains results for Cloudflare and Cloudfront.successful_results.txt: Contains successful scan results

`successful_results.txt`: Contains successful scan results
