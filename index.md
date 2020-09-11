## Directory of Real Time Event Sources

Pipedream is a serverless integration and compute platform. 

Pipedream receives data via event sources. Event sources are open source, run on Pipedream's infrastructure and collect data from your own application and/or services like Github, DropBox, Zoom, RSS feeds, and more.

Event sources emit new events produced by the service, which can trigger Pipedream workflows, or which you can consume using [Pipedream's REST API](https://docs.pipedream.com/api/rest/) or a private, real-time [SSE stream](https://docs.pipedream.com/api/sse/).

Here is the simplest event source possible, an HTTP event source:

```javascript
module.exports = {
  name: "http",
  version: "0.0.1",
  props: {
    http: "$.interface.http",
  },
  run(event) {
    console.log(event); // event contains the method, payload, etc.
  },
};
```

<a href="http://tod.ly/2UNkcs3"><img src="https://i.ibb.co/m0bBsSL/deploy-clean.png" height="35"></a>

Directory of Real Time Event Sources:
- [airtable](https://github.com/PipedreamHQ/pipedream/blob/master/components/airtable)
- [aws](https://github.com/PipedreamHQ/pipedream/blob/master/components/aws)
- [dev](https://github.com/PipedreamHQ/pipedream/blob/master/components/dev)
- [discord](https://github.com/PipedreamHQ/pipedream/blob/master/components/discord)
- [dropbox](https://github.com/PipedreamHQ/pipedream/blob/master/components/dropbox)
- [faunadb](https://github.com/PipedreamHQ/pipedream/blob/master/components/faunadb)
- [github](https://github.com/PipedreamHQ/pipedream/blob/master/components/github)
- [google-calendar](https://github.com/PipedreamHQ/pipedream/blob/master/components/google-calendar)
- [google-cloud](https://github.com/PipedreamHQ/pipedream/blob/master/components/google-cloud)
- [google-drive](https://github.com/PipedreamHQ/pipedream/blob/master/components/google-drive)
- [gorgias](https://github.com/PipedreamHQ/pipedream/blob/master/components/gorgias)
- [hacker-news](https://github.com/PipedreamHQ/pipedream/blob/master/components/hacker-news)
- [http](https://github.com/PipedreamHQ/pipedream/blob/master/components/http)
- [jotform](https://github.com/PipedreamHQ/pipedream/blob/master/components/jotform)
- [npm](https://github.com/PipedreamHQ/pipedream/blob/master/components/npm)
- [pipedream](https://github.com/PipedreamHQ/pipedream/blob/master/components/pipedream)
- [rss](https://github.com/PipedreamHQ/pipedream/blob/master/components/rss)
- [slack](https://github.com/PipedreamHQ/pipedream/blob/master/components/slack)
- [spotify](https://github.com/PipedreamHQ/pipedream/blob/master/components/spotify)
- [stripe](https://github.com/PipedreamHQ/pipedream/blob/master/components/stripe)
- [twilio](https://github.com/PipedreamHQ/pipedream/blob/master/components/twilio)
- [twitter-labs](https://github.com/PipedreamHQ/pipedream/blob/master/components/twitter-labs)
- [twitter](https://github.com/PipedreamHQ/pipedream/blob/master/components/twitter)
- [typeform](https://github.com/PipedreamHQ/pipedream/blob/master/components/typeform)
- [yahoo/fantasy-sports](https://github.com/PipedreamHQ/pipedream/blob/master/components/yahoo/fantasy-sports)
- [youtube](https://github.com/PipedreamHQ/pipedream/blob/master/components/youtube)
- [zoom-admin](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom-admin)
- [zoom](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom)

## Contribute

Do you want add a real time event source?  If so, check out the [Component API](https://github.com/PipedreamHQ/pipedream/blob/master/COMPONENT-API.md) and [Quickstart](https://github.com/PipedreamHQ/pipedream/blob/master/QUICKSTART.md).

You can get help [on our public Slack](https://pipedream.com/community) or [reach out to our team directly](https://docs.pipedream.com/support/) with any questions or feedback. We'd love to hear from you!

## Found a Bug? Have a Feature to suggest?

Before adding an issue, please search the [existing issues](https://github.com/PipedreamHQ/pipedream/issues) or [reach out to our team](https://docs.pipedream.com/support/) to see if a similar request already exists.

If an issue exists, please [add a reaction](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-conversations-on-github) or comment on your specific use case.
