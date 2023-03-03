### API Gateway Transaction Log Formatter

It is common when troubleshooting to want to share downloads from Traffic
Monitor, however the only two options are either to get a trace file with
only the traces, or a JSON file which has everything but is hard to read.

This HTML file contains some JavaScript that allows you to select a JSON
file exported from Traffic Monitor, then displays it in a format similar
to what you see when viewing the transaction on 8090, complete with all
legs of the transaction.

This allows one to share JSON exports from 8090 while making it easy to 
view them after export.

# Usage

Open the HTML file in this repo any browser, then select the JSON export
using the Browse button on the page.
