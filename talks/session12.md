# Death by a thousand commits
## Kyle d'Oliveira

### Automate the debt away - N+1 queries:

rails .includes - limitations
- manual effort
  - query in controller, n+1 in serializer
- only fixes one instance

[jit_preloader gem](https://github.com/clio/jit_preloader)
This gem provides a "magic bullet" that can remove most N+1 queries in the application.

### Clean up code you don't use

[dead_code_detector](https://github.com/clio/dead_code_detector)
DeadCodeDetector is a gem which finds code that hasn't been used in production environments so that it can be removed.
[coverband](https://github.com/danmayer/coverband)
A gem to measure production code usage, showing a counter for the number of times each line of code that is executed.

### Make is easier to keep the lights on

[marginalia](https://github.com/basecamp/marginalia)
Attach comments to your ActiveRecord queries.
[ActiveSupport::Notifications](https://api.rubyonrails.org/classes/ActiveSupport/Notifications.html)
provides an instrumentation API for Ruby.

### Keep the bad patterns out

[rubocop]()
[Shitlist Driven Development](http://sirupsen.com/shitlists/)
