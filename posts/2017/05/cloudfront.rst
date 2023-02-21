.. title: CloudFront Integration & HTTPS
.. slug: cloudfront
.. date: 2017-05-07 18:33:18 UTC-05:00
.. tags: AWS,Website,Updates,CloudFront,CDN,HTTPS
.. category: updates
.. link: 
.. description: Added CloudFront integration & restored HTTPS
.. type: text

I noticed that `some posts </posts/2017/04/weegames-updated.html>`_ had links with `absolute urls using https <https://news.wiseeyesent.com/posts/2017/04/relocated-to-aws-s3.html>`_. This was causing issues as S3 hosting does not support HTTPS due to the hostname convention or possibly some other reason. I've applied a `CloudFront CDN <https://aws.amazon.com/cloudfront/>`_ `distribution <https://d28u65npl4fudj.cloudfront.net/>`_ using my existing `letsencrypt <https://letsencrypt.org/>`_ SSL certificate to re-enable HTTPS traffic on this sub-domain. You may have noticed intermittent disruption today while this was being worked on. The same will be applied to the `Games site <//games.wiseeyesent.com/>`_ shortly.
