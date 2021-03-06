nagios_timeperiod
=================

The Nagios type timeperiod. This resource type is autogenerated
using the model developed in
[Naginator](http://projects.puppetlabs.com/projects/naginator),
and all of the Nagios types are generated using the same code and
the same library.

This type generates Nagios configuration statements in
Nagios-parseable configuration files. By default, the statements
will be added to `/etc/nagios/nagios_timeperiod.cfg`, but you can
send them to a different file by setting their `target` attribute.

You can purge Nagios resources using the `resources` type, but
*only* in the default file locations. This is an architectural
limitation.

### Parameters

#### alias

Nagios configuration file parameter.

#### ensure

The basic property that the resource should be in. Valid values are
`present`, `absent`.

#### exclude

Nagios configuration file parameter.

#### friday

Nagios configuration file parameter.

#### monday

Nagios configuration file parameter.

#### provider

The specific backend for provider to use. You will seldom need to
specify this -- Puppet will usually discover the appropriate
provider for your platform. Available providers are:

-   **naginator**:

#### register

Nagios configuration file parameter.

#### saturday

Nagios configuration file parameter.

#### sunday

Nagios configuration file parameter.

#### target

target

#### thursday

Nagios configuration file parameter.

#### timeperiod\_name

-   **namevar**

The name parameter for Nagios type timeperiod

#### tuesday

Nagios configuration file parameter.

#### use

Nagios configuration file parameter.

#### wednesday

Nagios configuration file parameter.


* * * * *

