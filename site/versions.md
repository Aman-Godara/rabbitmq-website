<!--
Copyright (c) 2007-2021 VMware, Inc. or its affiliates.

All rights reserved. This program and the accompanying materials
are made available under the terms of the under the Apache License,
Version 2.0 (the "License”); you may not use this file except in compliance
with the License. You may obtain a copy of the License at

https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Release Series

## <a id="overview" class="anchor" href="#overview">Overview</a>

This guide explains what release series of RabbitMQ (e.g. `3.8.x`) are currently covered
by general or extended support policies, and what series are no longer supported.

For guidance on upgrades, see the [Upgrade](/upgrade.html) and [Blue/Green Deployment Upgrade](/blue-green-upgrade.html) guides.

## <a id="currently-supported" class="anchor" href="#currently-supported">Currently Supported Release Series</a>

<table class="release-series">
  <tr>
    <th>Version</th>
    <th>Latest Patch</th>
    <th>First Release</th>
    <th>End of General Support<sup>1</sup></th>
    <th>End of Extended Support<sup>2</sup></th>
    <th>In service for</th>
  </tr>

  <tr>
    <td>3.8</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/&version-server-tag;" target="_blank">&version-server;</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.8.0" target="_blank">1 October 2019</a></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

<sup>1</sup> **General Support** means patch releases that are [produced regularly](/changelog.html) based on the feedback of
open source users and users with a [commercial support contract](/contact.html).

<sup>2</sup> **Extended Support** means only *security patches* and *high-severity issues* reported by users
with a [commercial support contract](/contact.html).


## <a id="" class="anchor" href="#next-release-series">Next Release Series</a>

This release calendar presents the scheduled milestones for the release cycle
of RabbitMQ 3.9.0. **Last updated on Monday, 12 July 2021.**

<table class="release-series">
  <tr>
    <th>Milestone</th>
    <th>Anticipated Date</th>
    <th>Actual Date</th>
    <th>Notes</th>
  </tr>

  <tr>
    <td>Code freeze</td>
    <td style="white-space: nowrap;">5 July 2021</td>
    <td style="white-space: nowrap;">7 July 2021</td>
    <td>No new features or refactorings before the final release, only bug fixes</td>
  </tr>

  <tr>
    <td>3.9.0-rc.1 build starts</td>
    <td style="white-space: nowrap;">9 July 2021</td>
    <td style="white-space: nowrap;">9 July 2021</td>
    <td>CI produces &amp; publishes all artefacts</td>
  </tr>

  <tr>
    <td><strong><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.9.0-rc.1">3.9.0-rc.1 is announced</a></strong></td>
    <td style="white-space: nowrap;">12 July 2021</td>
    <td style="white-space: nowrap;">9 July 2021</td>
    <td>First release candidate is announced &amp; made public for testing</td>
  </tr>

  <tr>
    <td>3.9.0-rc.2 build starts</td>
    <td style="white-space: nowrap;">16 July 2021</td>
    <td style="white-space: nowrap;"></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>3.9.0-rc.2 is announced</strong></td>
    <td style="white-space: nowrap;">19 July 2021</td>
    <td style="white-space: nowrap;"></td>
    <td></td>
  </tr>

  <tr>
    <td>3.9.0-rc.3</td>
    <td style="white-space: nowrap;">TBD</td>
    <td style="white-space: nowrap;"></td>
    <td>If new issues are reported, a new RC with fixes is made available for testing</td>
  </tr>

  <tr>
    <td>3.9.0 build starts</td>
    <td style="white-space: nowrap;">23 July 2021</td>
    <td style="white-space: nowrap;"></td>
    <td>Final release is built &amp; published</td>
  </tr>

  <tr>
    <td><strong>3.9.0 is announced</strong></td>
    <td style="white-space: nowrap;">26 July 2021</td>
    <td style="white-space: nowrap;"></td>
    <td>Final release is announced &amp; made public</td>
  </tr>
</table>

## <a id="out-of-support" class="anchor" href="#out-of-support">Release Series That are Out of Support</a>

<table class="release-series">
  <tr>
    <th>Version</th>
    <th>Final Patch</th>
    <th>First Release</th>
    <th>End of Life</th>
    <th>In service for</th>
  </tr>

  <tr>
    <td>3.7</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.7.28" target="_blank">3.7.28</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.7.0" target="_blank">28 November 2017</a></td>
    <td>30 September 2020</td>
    <td>34 months</td>
  </tr>

  <tr>
    <td>3.6</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_6_16" target="_blank">3.6.16</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_6_0" target="_blank">22 December 2015</a></td>
    <td>31 May 2018</td>
    <td>29 months</td>
  </tr>

  <tr>
    <td>3.5</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_5_8" target="_blank">3.5.8</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_5_0" target="_blank">11 March 2015</a></td>
    <td>31 October 2016</td>
    <td>20 months</td>
  </tr>

  <tr>
    <td>3.4</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_4_4" target="_blank">3.4.4</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_4_0" target="_blank">21 October 2014</a></td>
    <td>31 October 2015</td>
    <td>12 months</td>
  </tr>

  <tr>
    <td>3.3</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_3_5" target="_blank">3.3.5</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_3_0" target="_blank">2 April 2014</a></td>
    <td>31 March 2015</td>
    <td>12 months</td>
  </tr>

  <tr>
    <td>3.2</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_2_4" target="_blank">3.2.4</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_2_0" target="_blank">23 October 2013</a></td>
    <td>31 October 2014</td>
    <td>12 months</td>
  </tr>

  <tr>
    <td>3.1</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_1_5" target="_blank">3.1.5</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_1_0" target="_blank">1 May 2013</a></td>
    <td>30 April 2014</td>
    <td>12 months</td>
  </tr>

  <tr>
    <td>3.0</td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_0_4" target="_blank">3.0.4</a></td>
    <td><a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v3_0_0" target="_blank">19 November 2012</a></td>
    <td>30 November 2013</td>
    <td>12 months</td>
  </tr>
</table>

To learn more about individual releases, please see the [change log](/changelog.html).


## <a id="prior-to-v3x" class="anchor" href="#prior-to-v3x">Versions prior to v3.x</a>

RabbitMQ <a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v2_0_0" target="_blank">v2.0.0</a> was released on 24 August 2010.
<br />It reached end of life on 31 December 2012 as <a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v2_8_7" target="_blank">v2.8.7</a>.

RabbitMQ v1.0.0 was released on 1 July 2007.
<br />It reached end of life on 31 December 2010 as <a href="https://github.com/rabbitmq/rabbitmq-server/releases/tag/rabbitmq_v1_8_1" target="_blank">v1.8.1</a>.
