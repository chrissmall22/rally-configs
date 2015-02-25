Rally-Configs 
=============
**Example configs and tools to create rally benchmark and verification files. These configs can be used for acceptance testing or to capture performance metrics of OpenStack deployments**

Author: Chris Small, Hewlett Packard


Usage Example
-------------

# Create Benchmark Config 
generate_rally_bm_config.py full_bm.yaml

# Run Benchmarks
rally task start full_bm.yaml

# Report on last Benchmark Run
rally task report --html --output-file=report.html

# List Tasks 
rally task list

