Shout! (via BOSH)
=================

A notifications gateway for helping your little robot friends to
be heard.

To deploy it, you can use the manifests that come with this repo:

    bosh -e <your-bosh-director> -d shout \
         -v slack_webhook=https://...your-slack-webhook... \
         manifests/shout.yml

Then, you can interact with it on the standard port, 7109, via the
[Concourse resource][concourse], or just [using curl][api]

How Do I Contribute?
--------------------

  1. Fork this repo
  2. Create your feature branch (`git checkout -b my-new-feature`)
  3. Commit your changes (`git commit -am 'Added some feature'`)
  4. Push to the branch (`git push origin my-new-feature`)
  5. Create a new Pull Request in Github
  6. Profit!


[concourse]: https://github.com/jhunt/shout-resource
[api]:       https://github.com/jhunt/shout/blob/master/API.md
