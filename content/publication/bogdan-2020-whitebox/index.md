---
title: "White-box Compression: Learning and Exploiting Compact Table Representations"
date: 2019-01-09
publishDate: 2019-01-09T08:31:21.643084Z
authors: ["Bogdan Guita", "Diego Tomé", "Peter Boncz"]
publication_types: ["2"]
abstract: "We formulate a conceptual model forwhite-box compression,which represents thelogicalcolumns in tabular data as anopenly defined function over some actually storedphysicalcolumns.  Each block of data should thus go accompanied bya  header  that  describes  this  functional  mapping.   Becausethese  compression  functions  are  openly  defined,  databasesystems can exploit them using query optimization and dur-ing  execution,  enabling  e.g.   better  filter  predicate  push-down.   In  addition,  we  show  that  white-box  compressionis able to identify a broad variety of new opportunities forcompression,  leading  to  much  better  compression  factors.These opportunities are identified using anautomatic learn-ingprocess that learns the functions from the data.  We pro-vide a recursive pattern-driven algorithm for such learning.Finally, we demonstrate the effectiveness of white-box com-pression on a new benchmark we contribute hereby: thePub-lic BI benchmarkprovides a rich set of real-world datasets.We  believe  our  basic  prototype  for  white-box  compres-sion opens the way for future research into transparent com-pressed data representations on the one hand and databasesystem architectures that can efficiently exploit these on theother,  and  should  be  seen  as  another  step  into  the  direc-tion of data management systems that are self-learning andoptimize themselves for the data they are deployed on."
featured: false
publication: "*Proceedings of the Conference on Innovative Data Systems Research (CIDR)*"
url_pdf: "files/whitebox.pdf"
url_code: "https://github.com/diegomestre2/whitebox_compression"
---

