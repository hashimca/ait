<img src="https://imgs.xkcd.com/comics/git.png" title="If that doesn&#39;t fix it, git.txt contains the phone number of a friend of mine who understands git. Just wait through a few minutes of &#39;It&#39;s really pretty simple, just think of branches as...&#39; and eventually you&#39;ll learn the commands that will fix everything." alt="Git" />

*Image from Randall Munroe's brilliant webcomic [XKCD](https://xkcd.com)*


### Resources
- [Git documentation](http://git-scm.com/docs)
- [Markdown syntax](http://guides.github.com/features/mastering-markdown/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [GitHub Help articles](https://help.github.com)
- [GitHub Training YouTube videos](https://www.youtube.com/user/GitHubGuides/videos?view=0&sort=dd&live_view=500&flow=list)
- Git-aware prompt:

```bash
git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
```

