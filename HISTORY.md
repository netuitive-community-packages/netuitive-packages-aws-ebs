## Release History

### Version next
* Remove metrics: netuitive.aws.ebs.busytimebytespersecond
                  netuitive.aws.ebs.writebytespersec
                  netuitive.aws.ebs.readbytespersec
                  netuitive.aws.ebs.busypercent
                  netuitive.aws.ebs.writeopspersec
                  netuitive.aws.ebs.readopspersec
                  netuitive.aws.ebs.totalbytespersec
                  netuitive.aws.ebs.totalops
                  netuitive.aws.ebs.averagereadlatency
                  netuitive.aws.ebs.averagewritelatency
                  netuitive.aws.ebs.totalbytes
* Replace deleted metrics with other ones in dashboards AWS EBS Summary AWS EBS Element Detail                          

* aws.ebs.elevated.queue.length policy has been split into 2 policies to separate critical and warning thresholds

### Version 1.7.0

* Adjusted build to use metricly-cli for validation
* Convert most computed metrics to new format
* Fix bad merge that removed validMin setting from queuelengthdifferential

### Version 1.6.0

* Changed the scope element type to an array
* Add the depleted burst balance and high IOPS utilization policy

### Version 1.5.0

* Update to Element Details dashboard layout
* Update to Summary dashboard widgets

### Version 1.4.0

* Updated dashboard layouts for gridstack

### Version 1.3.3

* Updated package compatibilities.

### Version 1.3.2

* Bug fix for the multi-metric widgets on the element detail page.

### Version 1.3.1

* Fixed bug with the Events widget on the Element Detail Page.

### Version 1.3.0

* Added EBS-specific element detail page.
* Changed "sum" to "avg" on summary dashboard widgets.

### Version 1.2.0

* Added units to metrics.

### Version 1.1.0

* Added summary dashboard.

### Version 1.0.0

* Initial production release of the package for monitoring AWS Elastic Block Storage (EBS) resources.
