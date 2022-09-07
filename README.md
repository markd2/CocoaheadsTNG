# CocoaheadsTNG

Updating CocoaHead.org

Slack discussion at https://cocoaheads.slack.com/archives/C08L3EGF2/p1661702063109989

Two ideas:
  * Swift on the server / Vapor / porting or migrating the existing Cocoaheads.org schema
    - more conventional website experience
    - requires learning Vapor
    - requires hosting and on-going maintenance
    - maybe can get some volunteer contributors

  * Use a static site generator, where organizers can edit a YAML file and make PR
    to update their info.  
    - https://github.com/NSCoderNight/NSCoderNight
    - Organizers probably are familiar with editing stuff like YAML and doing PRs
    - Still need to get permission to use their code (or start a clean reimplementation)

  * @hsoi has had success with self-hosting (on A2) Wordpress - https://blog.hsoi.com/2022/08/23/is-this-thing-on/ . 
    - it supports accounts. Can probably write a plugin that takes meeting locations and
      generates the google map
    - Wordpress has been around a long time, there's probably a Plugin For That.

