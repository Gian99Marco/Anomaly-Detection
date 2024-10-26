# Anomaly Detection on the "cs448b_ipasn" dataset

In this notebook we will analyze the "cs448b_ipasn" dataset which includes some network traffic data.

We will explore time series of communication between local computers (l_ipn) and remote resources (r_asn).

The dataset has approximately 21K rows and covers 10 local workstation IPs over a three month period.

Each row consists of four columns:
*   date: yyyy-mm-dd (from 2006-07-01 through 2006-09-30)
*   l_ipn: local IP (coded as an integer from 0-9)
*   r_asn: remote ASN (an integer which identifies the remote ISP)
*   f: flows (count of connnections for that day)


We will perform anomaly detection using different machine learning algorithms in order to understand if there have been any attacks or any anomalous behavior.
