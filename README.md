# rss2nostr
Convert RSS items into Nostr events

### Why rss2nostr?

RSS is one of those humble protocols that glues the web. It was born out of the same values (openness, data portability, ...) that are the foundation of Nostr.

You may not be aware, but you can already export most of the content you create and publish today into an RSS feed.
*   Most blog platforms allow users to make their content available as an RSS feed.
*   Most bookmark services allow users to create an RSS feed from their bookmarks.
*   Every podcast platforms generate an RSS feed for your show.

More generally, there are plenty of third-party services (e.g. RSS.app, IFTTT, ...) that enable the creation of RSS feeds for almost everything: social media feeds, job listings, events, etc.

On the other hand, Nostr is poised to become the new web infrastructure. It will dismantle the walled gardens we've been living in for too long and is already shaping an ecosystem of decentralized apps that will gradually replace centralized ones, one by one.

Connecting RSS and Nostr is obviously a necessary step to accelerate the transition toward this new web powered by Nostr.

### rss2nostr capabilities

rss2nostr should be able to accommodate the diverse needs of users and support various RSS feed variants. To achieve this, users can configure the behavior of rss2nostr in several ways. Here are some examples:
*   Depending on whether the `<description>` element contains a truncated or full version of the item, rss2nostr can be configured to display or hide the link to the original web item.
*   The content of the `<category>` element can be transformed into hashtags appended to the end of the description content.
*   Users can choose the type of events created by rss2nostr; for instance, an RSS feed from a Substack newsletter might create "long-form content" events.
*   The `<enclosure>` or `<media:content>` elements can be handled according to user preferences, such as being ignored, embedded, linked, or treated in other ways.
    

### rss2nostr UX

The goal is to make rss2nostr accessible to all types of users, including those with very limited technical skills.
To achieve this, we should aim to create a web app that allows users to:
*   Submit the RSS feed they want to convert into a stream of Nostr events
*   Specify the Nostr profile they would like to publish the events to
*   Define rules and parameters for converting RSS items into Nostr events

Furthermore, using a liberal open-source license may enable the development of competing web apps.

### Support this project

Just head over to the [Geyser page for rss2nostr](https://geyser.fund/project/rss2nostr).
Any contribution will be much appreciated, thanks!

This financial resources will be used
*   to attract and compensate the best Nostr developers
*   pay for the initial hosting costs of the rss2nostr web app  
    (hopefully, zaps from users will be sufficient to sustain the service)
