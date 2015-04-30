Can't find box on vagrant cloud
---

# Vagrant Version

1.7.3

# Missing Box

ffuenf/debian-8.0.0-amd64

Atlas URL: https://atlas.hashicorp.com/ffuenf/boxes/debian-8.0.0-amd64

# Output

```
➜  avril git:(master) ✗ vagrant up
Bringing machine 'default' up with 'vmware_fusion' provider...


==> default: Box 'ffuenf/debian-8.0.0-amd64' could not be found. Attempting to find and install...
    default: Box Provider: vmware_desktop, vmware_fusion, vmware_workstation
    default: Box Version: >= 0
==> default: Loading metadata for box 'ffuenf/debian-8.0.0-amd64'
    default: URL: https://atlas.hashicorp.com/ffuenf/debian-8.0.0-amd64
The box you're attempting to add doesn't support the provider
you requested. Please find an alternate box or use an alternate
provider. Double-check your requested provider to verify you didn't
simply misspell it.

If you're adding a box from HashiCorp's Atlas, make sure the box is
released.

Name: ffuenf/debian-8.0.0-amd64
Address: https://atlas.hashicorp.com/ffuenf/debian-8.0.0-amd64
Requested provider: ["vmware_desktop", "vmware_fusion", "vmware_workstation"]
```

# Steps to Reproduce

1. Use Vagrant VMWare Fusion provider
2. Git clone this repo `git clone
   https://github.com/fivetanley/missing-vagrant-box.git`
3. `cd missing-vagrant-box`
4. `vagrant up`
5. See the box not found.

# LICENSE (because why not lol)

The MIT License (MIT)

Copyright (c) 2015 Stanley Stuart

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
