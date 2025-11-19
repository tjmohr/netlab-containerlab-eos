# netlab using containerlab with Arista cEOS image
A simple setup of Netlab with Containerlab and Arista cEOS for network lab setups.  Please see the netlab documantation and containerlab documentation for more details.
[https://netlab.tools](https://netlab.tools)
[https://https://containerlab.dev/](https://containerlab.dev/)


Install python library dependencies
```bash
pip install -r requirements.txt
```
Test netlab using containerlab
```bash
netlab test clab
```
Bring up simple lab based on `toplogy.yml` file.
```bash
netlab up
```
