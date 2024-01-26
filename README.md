## ASN Recon
Recon scripts for gathering ASNs via organization name and filtering out shared-ASN to avoid out-of-scope domains

### Installation:
```bash
$ git clone https://github.com/MR-Prey3r/asn-recon.git
$ cd asn-recon
$ unzip asn-recon
```
### Usage:
To get all the available ASNs related to the org name provided (be sure to remove the unwanted org ASN)
```bash
echo "org name" | ./asn-grabber'
```

To get the non-shared ASN only
```bash
cat asn-list.txt | awk '{print $1}' | ./lone-asn
```

### Note:
Please note that these scripts are prototype projects so these may not be accurate!
