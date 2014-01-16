[![Build Status](https://travis-ci.org/rackerlabs/stacktach.png?branch=master)](https://travis-ci.org/rackerlabs/stacktach)

# StackTach

StackTach is a debugging / monitoring utility for OpenStack ([Open]StackTach[ometer]). StackTach can work with multiple datacenters including multi-cell deployments.

Watch the video here: http://www.youtube.com/watch?v=pZgwDHZ3wm0

## Overview
OpenStack has the ability to publish notifications to a RabbitMQ exchange as they occur. So, rather than pouring through reams of logs across multiple servers, you can now watch requests travel through the system from a single location.

A detailed description of the notifications published by OpenStack [is available here](http://wiki.openstack.org/SystemUsageData)

## Documentation
`cd` into the `docs` directory and run `make html` to get the installation and API docs. Or you can view the `rst` files [directly here](https://github.com/rackerlabs/stacktach/blob/master/docs/setup.rst)
