# CloudQuarryWordlists

CloudQuarryWordlists is a repository containing files and paths identified in public Amazon Machine Images (AMIs). This was achieved as part of [AWS CloudQuarry: Digging for Secrets in Public AMIs](https://securitycafe.ro/2024/05/08/aws-cloudquarry-digging-for-secrets-in-public-amis/), a research project conducted by [Eduard Agavriloae](https://www.linkedin.com/in/eduard-k-agavriloae/) and [Matei Josephs](https://www.linkedin.com/in/matei-anthony-josephs/). This research was presented at [DEF CON 32](https://media.defcon.org/DEF%20CON%2032/DEF%20CON%2032%20presentations/DEF%20CON%2032%20-%20Eduard%20Agavriloae%20Matei%20Josephs%20-%20AWS%20CloudQuarry%20-%20Digging%20for%20Secrets%20in%20Public%20AMIs.pdf). 

**Please note that the wordlists are sorted in descending order by frequency. Thus, the filenames towards the beginning of the lists are the most popular, whilst the ones towards the end of the lists are the least popular.**

## How the wordlists were created
For this research, we ended up scanning the contents of 26,778 public AMIs for secrets. However, for future reference we also kept a record of all files discovered across the scanned AMIs. Our aim behind doing this was to aid future research by showing what types of files and directories are typically found within AMIs. 

More details about the research can be found on [SecurityCafe](https://securitycafe.ro/2024/05/08/aws-cloudquarry-digging-for-secrets-in-public-amis/). 

[Saw_your_packet](https://github.com/saw-your-packet) will publish our tooling shortly.

## License

[MIT](https://choosealicense.com/licenses/mit/)
