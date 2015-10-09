Zendrive Scores
---------------

The safety and efficiency of your fleet drivers can make or break your bottom line. Zendrive SDK was built to give fleet managers insight into the quality and safety of their drivers based on detailed driving behavior. By accessing phone sensors and combining that data with context about the drive time and place, Zendrive can identify both safe and risky driving - allowing fleet managers to take action before poor driving becomes a liability. The main areas of interest are cautiousness, control and focus. Zendrive mobile SDK automatically detects the start and end of driving (called trips) and collects sensor data (GPS / accelerometer / gyroscope etc) throughout the trip. Zendrive employs state of the art data analysis and machine learning algorithms to compute various driver behavior scores. The scores are expressed as a number between 0 to 100 or -1 if they are not yet available. High values correspond to better driving practices.


ec2_settings
------------

.. csv-table::
    :header: "Parameter", "Description"
    :widths: 15, 50

    "**label**", "A list of labels that identify the cluster. At least one label must be provided when cloning a cluster"
    "`ec2_settings`", "The Amazon EC2 Settings."
    "`hadoop_settings`", "The Hadoop Cluster Settings."
    "`security_settings`", "The Instance Security Settings."
    "`presto_settings`_", "The Presto Settings."
    "disallow_cluster_termination", "Prevents auto-termination of the cluster after a prolonged period of disuse"
    "enable_ganglia_monitoring", "Enable `Ganglia <http://ganglia.sourceforge.net/>`__ monitoring for the cluster."
    "node_bootstrap_file", "A file that gets executed on every node of the cluster at boot time. You can use this to customize your cluster nodes by setting up environment variables, installing required packages, etc."
