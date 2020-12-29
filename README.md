# Login Redirect extension for phpBB

Redirects a user to a chosen topic/announcement when they log in.

[![Build Status](https://github.com/david63/loginredirect/workflows/Tests/badge.svg)](https://github.com/phpbb-extensions/david63/loginredirect)
[![License](https://poser.pugx.org/david63/loginredirect/license)](https://packagist.org/packages/david63/loginredirect)
[![Latest Stable Version](https://poser.pugx.org/david63/loginredirect/v/stable)](https://packagist.org/packages/david63/loginredirect)
[![Latest Unstable Version](https://poser.pugx.org/david63/loginredirect/v/unstable)](https://packagist.org/packages/david63/loginredirect)
[![Total Downloads](https://poser.pugx.org/david63/loginredirect/downloads)](https://packagist.org/packages/david63/loginredirect)
[![codecov](https://codecov.io/gh/david63/loginredirect/branch/master/graph/badge.svg?token=D2500PgRex)](https://codecov.io/gh/david63/loginredirect)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1e345cbce32b4f42b577fffca97d4a99)](https://www.codacy.com/manual/david63/loginredirect?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=david63/loginredirect&amp;utm_campaign=Badge_Grade)

[![Compatible](https://img.shields.io/badge/compatible-phpBB:3.2.x-blue.svg)](https://shields.io/)
[![Compatible](https://img.shields.io/badge/compatible-phpBB:3.3.x-blue.svg)](https://shields.io/)

## Minimum Requirements
* phpBB 3.3.0
* PHP 7.1.3

## Install
1. [Download the latest release](https://github.com/david63/loginredirect/archive/3.2.zip) and unzip it.
2. Unzip the downloaded release and copy it to the `ext` directory of your phpBB board.
3. Navigate in the ACP to `Customise -> Manage extensions`.
4. Look for `Login redirect` under the Disabled Extensions list and click its `Enable` link.

## Usage
1. Navigate in the ACP to `Extensions -> Login redirect -> Manage redirects`.
2. Apply the settings that you require.

## Uninstall
1. Navigate in the ACP to `Customise -> Manage extensions`.
2. Click the `Disable` link for `Login redirect`.
3. To permanently uninstall, click `Delete Data`, then delete the loginredirect folder from `phpBB/ext/david63/`.

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2020 - David Wood