---
permalink: /research/
title: "Research"
---

My research is interdisciplinary encompassing, social media/computational social science, web/data science, web archiving, and (local) news.

## [StoryGraph](https://web.archive.org/storygraph/)

StoryGraph provides a collection tools that analyze the news cycle by computing the similarity of news stories across 17 US news sources. [USA](https://web.archive.org/storygraph/graphs/usa/) generates a news similarity graph every 10 minutes by computing the similarity of news stories from 17 US news sources across the partisanship spectrum (left, center, and right). In these graphs, the nodes represent news articles, and an edge between a pair of nodes represents a high degree of similarity between the nodes (similar news stories). The graphs track the development of a news events.

<table align="center">
  <tr>
    <td>
      <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=98&hist=1440&t=2019-03-21T16:26:25" target="_blank" title="Click me! Slow news cycle story graph">
        <img src="/images/research/sample_graph_1.png" alt="Slow news cycle story graph" class="img">
      </a>
    </td>
    <td>
      <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=115&hist=1440&t=2019-11-17T19:15:38" target="_blank" title="Click me! Split attention story graph">
        <img src="/images/research/sample_graph_2.png" alt="Split attention story graph" class="img">
      </a>
    </td>
    <td>
      <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=135&hist=1440&t=2019-03-24T22:32:21" target="_blank" title="Click me! Mueller report story graph">
        <img src="/images/research/sample_graph_3.png" alt="Mueller report story graph" class="img">
      </a>
    </td>
  </tr>
  <caption align="bottom">Three news similarity graphs illustrating the dynamics of the news cycle. In these graphs, a single node represents a news article, a connected component (multiple connected nodes) represents a single news story reported by the connected nodes. StoryGraph uses the average degree (attention score) of the connected components to quantify the level of attention the topics in the news stories receive. <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=98&hist=1440&t=2019-03-21T16:26:25" target="_blank">The first graph</a> shows what is often referred to as a slow news day; low overlap across different news media organizations. <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=115&hist=1440&t=2019-11-17T19:15:38" target="_blank">The second graph</a> shows a scenario where the attention of the media is split across multiple news stories. <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=135&hist=1440&t=2019-03-24T22:32:21">The third graph</a> for the "AG William Barr's release of his principal conclusions of the Mueller Report" story shows a major news event; high degree of overlap/connectivity across different news media organizations.</caption>
</table>

## [StoryGraphBot](https://twitter.com/storygraphbot)

<a href="https://twitter.com/storygraphbot">StoryGraphBot</a> is a Twitter bot that runs every hour, tracking top news stories and creating tweet threads that report updates (rising/falling/same attention) of the stories. See also, <a href="https://ws-dl.blogspot.com/2021/05/2021-05-10-chronicling-life-cycle-of.html" target="_blank">Chronicling the life-cycle of top new stories with StoryGraphBot</a>.


<figure>
  <a href="https://web.archive.org/storygraph/graphs/usa/#cursor=135&hist=1440&t=2019-03-24T22:32:21" target="_blank" title="Story Attention Dynamics Graph">
    <img src="/images/research/sgbot_tracking_stories.png" alt="Story Attention Dynamics Graph" class="img">
  </a>
  <figcaption>
    Story Attention Dynamics chart illustrating the life-cycle of two top news stories from May 18, 2018 -- May 19, 2018. Each line (red or blue) represents a top news story. The x-axis represents time while the y-axis represents the average degree of Connected Components (representation of story). Within our window of observation, the <a href="https://twitter.com/storygraphbot/status/1388942915574112264" target="_blank">Santa Fe High School Shooting story received peak attention on Friday May 18, 2018 at 4:40PM, this attention waned with the lowest point coinciding with the rise of a new story, the <a href="https://twitter.com/storygraphbot/status/1388943136127393796" target="_blank">Royal Wedding of Prince Harry and Meghan Markle
  </figcaption>
</figure>

