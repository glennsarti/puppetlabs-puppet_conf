# Reference
<!-- DO NOT EDIT: This document was generated by Puppet Strings -->

## Table of Contents

**Tasks**

* [`init`](#init): Inspect puppet agent configuration settings

## Tasks

### init

Inspect puppet agent configuration settings

**Supports noop?** false

#### Parameters

##### `action`

Data type: `Enum[get, set]`

The operation (get, set) to perform on the configuration setting

##### `section`

Data type: `Optional[String[1]]`

The section of the config file. Defaults to main

##### `setting`

Data type: `String[1]`

The name of the config entry to set/get

##### `value`

Data type: `Optional[String[1]]`

The value you are setting. Only required for set
