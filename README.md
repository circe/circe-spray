# circe-spray

[![Build status](https://img.shields.io/github/workflow/status/circe/circe-spray/Continuous%20Integration.svg)](https://github.com/circe/circe-spray/actions)
[![Coverage status](https://img.shields.io/codecov/c/github/circe/circe-spray/master.svg)](https://codecov.io/github/circe/circe-spray)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-green.svg)](https://gitter.im/circe/circe)
[![Maven Central](https://img.shields.io/maven-central/v/io.circe/circe-spray_2.11.svg)](https://maven-badges.herokuapp.com/maven-central/io.circe/circe-spray_2.11)

This project provides support for using [circe][circe] to provide JSON marshallers for
[Spray][spray]. Note that Spray is no longer being actively maintained, and new projects should
typically use [Akka HTTP][akka-http] (with [akka-http-circe][akka-http-circe] for circe
integration) or a library like [Finch][finch] instead.

There's not a lot of documentation, but we do publish the [API docs][api-docs].

## Contributors and participation

All circe projects support the [Typelevel][typelevel] [code of conduct][code-of-conduct] and we want
all of their channels (Gitter, GitHub, etc.) to be welcoming environments for everyone.

Please see the [circe contributors' guide][contributing] for details on how to submit a pull
request.

## License

circe-spray is licensed under the **[Apache License, Version 2.0][apache]**
(the "License"); you may not use this software except in compliance with the
License.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[akka-http]: http://doc.akka.io/docs/akka-http/current/scala.html
[akka-http-circe]: https://github.com/hseeberger/akka-http-json/tree/master/akka-http-circe
[apache]: http://www.apache.org/licenses/LICENSE-2.0
[api-docs]: https://circe.github.io/circe-spray/api/#io.circe.spray.package
[circe]: https://github.com/circe/circe
[code-of-conduct]: http://typelevel.org/conduct.html
[contributing]: https://circe.github.io/circe/contributing.html
[finch]: https://github.com/finagle/finch
[http4s]: https://github.com/http4s/http4s
[spray]: https://github.com/spray/spray
[typelevel]: http://typelevel.org/
