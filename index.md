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
- [airtable](https://github.com/PipedreamHQ/pipedream/blob/master/components/airtable/readme.md)
- [aws](https://github.com/PipedreamHQ/pipedream/blob/master/components/aws/readme.md)
- [dev](https://github.com/PipedreamHQ/pipedream/blob/master/components/dev/readme.md)
- [discord](https://github.com/PipedreamHQ/pipedream/blob/master/components/discord/readme.md)
- [dropbox](https://github.com/PipedreamHQ/pipedream/blob/master/components/dropbox/readme.md)
- [faunadb](https://github.com/PipedreamHQ/pipedream/blob/master/components/faunadb/readme.md)
- [github](https://github.com/PipedreamHQ/pipedream/blob/master/components/github/readme.md)
- [google-calendar](https://github.com/PipedreamHQ/pipedream/blob/master/components/google-calendar/readme.md)
- [google-cloud](https://github.com/PipedreamHQ/pipedream/blob/master/components/google-cloud/readme.md)
- [google-drive](https://github.com/PipedreamHQ/pipedream/blob/master/components/google-drive/readme.md)
- [gorgias](https://github.com/PipedreamHQ/pipedream/blob/master/components/gorgias/readme.md)
- [hacker-news](https://github.com/PipedreamHQ/pipedream/blob/master/components/hacker-news/readme.md)
- [http](https://github.com/PipedreamHQ/pipedream/blob/master/components/http/readme.md)
- [jotform](https://github.com/PipedreamHQ/pipedream/blob/master/components/jotform/readme.md)
- [npm](https://github.com/PipedreamHQ/pipedream/blob/master/components/npm/readme.md)
- [pipedream](https://github.com/PipedreamHQ/pipedream/blob/master/components/pipedream/readme.md)
- [rss](https://github.com/PipedreamHQ/pipedream/blob/master/components/rss/readme.md)
- [slack](https://github.com/PipedreamHQ/pipedream/blob/master/components/slack/readme.md)
- [spotify](https://github.com/PipedreamHQ/pipedream/blob/master/components/spotify/readme.md)
- [stripe](https://github.com/PipedreamHQ/pipedream/blob/master/components/stripe/readme.md)
- [twilio](https://github.com/PipedreamHQ/pipedream/blob/master/components/twilio/readme.md)
- [twitter-labs](https://github.com/PipedreamHQ/pipedream/blob/master/components/twitter-labs/readme.md)
- [twitter](https://github.com/PipedreamHQ/pipedream/blob/master/components/twitter/readme.md)
- [typeform](https://github.com/PipedreamHQ/pipedream/blob/master/components/typeform/readme.md)
- [yahoo/fantasy-sports](https://github.com/PipedreamHQ/pipedream/blob/master/components/yahoo/fantasy-sports/readme.md)
- [youtube](https://github.com/PipedreamHQ/pipedream/blob/master/components/youtube/readme.md)
- [zoom-admin](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom-admin/readme.md)
- [zoom](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/readme.md)

## Contribute

Do you want add a real time event source?  If so, check out the [Component API](https://github.com/PipedreamHQ/pipedream/blob/master/COMPONENT-API.md) and [Quickstart](https://github.com/PipedreamHQ/pipedream/blob/master/QUICKSTART.md).

You can get help [on our public Slack](https://pipedream.com/community) or [reach out to our team directly](https://docs.pipedream.com/support/) with any questions or feedback. We'd love to hear from you!

## Found a Bug? Have a Feature to suggest?

Before adding an issue, please search the [existing issues](https://github.com/PipedreamHQ/pipedream/issues) or [reach out to our team](https://docs.pipedream.com/support/) to see if a similar request already exists.

If an issue exists, please [add a reaction](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-conversations-on-github) or comment on your specific use case.
