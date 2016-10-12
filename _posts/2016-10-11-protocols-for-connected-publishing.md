---
ID: 22
post_title: Protocols for Connected Publishing
author: sah
post_date: 2016-10-11 20:48:30
post_excerpt: ""
layout: post
permalink: >
  http://publishingxml.org/2016/10/11/protocols-for-connected-publishing/
published: true
---
The Publishing XML project (<a href="https://github.com/BlackEarth/publishing-xml" target="_blank">https://github.com/BlackEarth/publishing-xml</a>) defines a shared set of XML vocabularies (“schemas”) for connected publishing. The purpose is to define an XML flavor that covers all publishing needs while maintaining maximum compatibility with existing systems. It fills a gap in the publishing ecosystem: There has been no comprehensive set of schemas, and corresponding tools, to cover the needs of publishing in general. Publishing XML is to publishing what EPUB3 is to digital publishing. Like EPUB3, it
<ul>
 	<li>makes use of the XHTML-flavor of HTML5 as the core content document type. This provides for maximum compatibility with other content systems.</li>
 	<li>makes use of the Dublin-Core and related vocabularies for publication metadata.</li>
 	<li>provides extra vocabulary and semantics for dealing with the needs of publishing that are not met by HTML5 semantics.</li>
</ul>
Unlike EPUB3, Publishing XML considers the semantic needs of all publishing, not just digital or ebook publishing.

The Publishing XML ecosystem also provides shared tools for using these schemas. So far there is:
<ul>
 	<li>pubxml — Python tools for working with Publishing XML. (<a href="https://github.com/BlackEarth/pubxml">https://github.com/BlackEarth/pubxml</a>)</li>
</ul>
To install the schemas, download / clone this repository to an appropriate location on your system.

If you would like to contribute, just fork the repository and start submitting pull requests. You also might want to read the community contract at some point—the publishing-xml project follows the protocol defined in the “Collective Code Construction Contract” (C4), as defined at <a href="https://rfc.zeromq.org/spec:42/C4/">https://rfc.zeromq.org/spec:42/C4/</a>.

The publishing-xml project and code base is licensed under the Mozilla Public License, v. 2 (MPL2), as defined in the LICENSE file. Each contributor owns his or her respective contributions and licenses it under the terms of the MPL2.