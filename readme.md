Cloudflare IP Range
===================

`mini-skirt/cloudflare-iprange`

A simple helper library related to Cloudflare IPv4 range and IPv6 range.


# Requirements

PHP (version > 7.2)

wikimedia/ip-set


# Usage Demo

```php
<?php
use MiniSkirt\Cloudflare\IPRange;

// $ipAddress = $_SERVER['HTTP_CF_CONNECTING_IP'];
// $ipAddress = $_SERVER['REMOTE_ADDR'];
IPRange::in($ipAddress);       //-> true | false

```