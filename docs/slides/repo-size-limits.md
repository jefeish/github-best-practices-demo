## Repository Size Limits

Limits of files you can track in regular Git repositories

<br>
<div style="font-size: 36px; text-align: justify; width: 80%; margin: 0% 10% 0% 10%;">

| Data            | Limit            |
|-----------------|------------------|
| Files >50 MB <100 MB | Warning from Git. Will still successfully push |
| Files >100 MB | GitHub blocks files larger than 100 MB. <br>Use [Git LFS](https://docs.github.com/en/enterprise-cloud@latest/repositories/working-with-files/managing-large-files/about-git-large-file-storage) |
| Browser upload max size| 25 MB |
| Repository [total size](https://github.com/github/git-sizer) |Ideally  <1 GB <br> Strongly recommended <5 GB |
| Release [attachments](https://docs.github.com/en/enterprise-cloud@latest/repositories/working-with-files/managing-large-files/about-large-files-on-github#distributing-large-binaries) | We don't limit the total size of the binary files. <br>Individual file must be <2 GB |
|Git LFS| <1 GB free storage and 1 GB a month of free bandwidth [*](https://docs.github.com/en/enterprise-cloud@latest/repositories/working-with-files/managing-large-files/about-storage-and-bandwidth-usage)

</div>