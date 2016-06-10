# NativeScript Documentation

Welcome to the NativeScript documentation content repository. This repository contains the content that lives at <http://docs.nativescript.org>, and is generated by [Jekyll](https://jekyllrb.com/).

## Multiple configurations

We have two Jekyll builds for the documentation that generate similar output: `nativescript` and `angular`. The former builds the vanilla NativeScript docs, while the latter discusses Angular2-specific topics. Most of the content is shared between the two, and several options are available to add environment-specific content:

1. Pages that appear in certain environment only. Adding an `environment: angular` to a page's front matter will mark that page as being available only in that environment. Other environment builds will exclude it. Pages not marked with `environment` will be shared across all environments.

2. Display different content on shared pages. This is possible via our environment-related block tags, named `angular` and `nativescript` respectively:
    ```
    {% nativescript %}Dependency properties...{% endnativescript %}

    {% angular %}Change detection...{% endangular %}[
    ```

## Contributors

The following is a list of all the people that have contributed to the NativeScript documentation. Thanks for your contributions!

Want to contribute? [Send a pull request!](https://help.github.com/articles/using-pull-requests/) [Ping us on Slack](http://developer.telerik.com/wp-login.php?action=slack-invitation) if you need help getting with git or GitHub, or for ideas on documentation pages you can help with.

[<img alt="tjvantoll" src="https://avatars.githubusercontent.com/u/544280?v=3&s=117" width="117">](https://github.com/tjvantoll)[<img alt="ErjanGavalji" src="https://avatars.githubusercontent.com/u/84975?v=3&s=117" width="117">](https://github.com/ErjanGavalji)[<img alt="ns-bot" src="https://avatars.githubusercontent.com/u/8101183?v=3&s=117" width="117">](https://github.com/ns-bot)[<img alt="tsonevn" src="https://avatars.githubusercontent.com/u/17448734?v=3&s=117" width="117">](https://github.com/tsonevn)[<img alt="vakrilov" src="https://avatars.githubusercontent.com/u/4092076?v=3&s=117" width="117">](https://github.com/vakrilov)[<img alt="N3ll" src="https://avatars.githubusercontent.com/u/12541122?v=3&s=117" width="117">](https://github.com/N3ll)

[<img alt="enchev" src="https://avatars.githubusercontent.com/u/5804953?v=3&s=117" width="117">](https://github.com/enchev)[<img alt="ikoevska" src="https://avatars.githubusercontent.com/u/3539221?v=3&s=117" width="117">](https://github.com/ikoevska)[<img alt="hamorphis" src="https://avatars.githubusercontent.com/u/1201857?v=3&s=117" width="117">](https://github.com/hamorphis)[<img alt="erikruth" src="https://avatars.githubusercontent.com/u/14181027?v=3&s=117" width="117">](https://github.com/erikruth)[<img alt="nsndeck" src="https://avatars.githubusercontent.com/u/5665150?v=3&s=117" width="117">](https://github.com/nsndeck)[<img alt="vchimev" src="https://avatars.githubusercontent.com/u/12251337?v=3&s=117" width="117">](https://github.com/vchimev)

[<img alt="atanasovg" src="https://avatars.githubusercontent.com/u/5878999?v=3&s=117" width="117">](https://github.com/atanasovg)[<img alt="Plamen5kov" src="https://avatars.githubusercontent.com/u/5918351?v=3&s=117" width="117">](https://github.com/Plamen5kov)[<img alt="teobugslayer" src="https://avatars.githubusercontent.com/u/5443453?v=3&s=117" width="117">](https://github.com/teobugslayer)[<img alt="hdeshev" src="https://avatars.githubusercontent.com/u/63219?v=3&s=117" width="117">](https://github.com/hdeshev)[<img alt="jasssonpet" src="https://avatars.githubusercontent.com/u/305639?v=3&s=117" width="117">](https://github.com/jasssonpet)[<img alt="ivanbuhov" src="https://avatars.githubusercontent.com/u/2405533?v=3&s=117" width="117">](https://github.com/ivanbuhov)

[<img alt="boevski" src="https://avatars.githubusercontent.com/u/10432616?v=3&s=117" width="117">](https://github.com/boevski)[<img alt="Mitko-Kerezov" src="https://avatars.githubusercontent.com/u/6683316?v=3&s=117" width="117">](https://github.com/Mitko-Kerezov)[<img alt="rosen-vladimirov" src="https://avatars.githubusercontent.com/u/8351653?v=3&s=117" width="117">](https://github.com/rosen-vladimirov)[<img alt="valentinstoychev" src="https://avatars.githubusercontent.com/u/4980822?v=3&s=117" width="117">](https://github.com/valentinstoychev)[<img alt="tzraikov" src="https://avatars.githubusercontent.com/u/3244426?v=3&s=117" width="117">](https://github.com/tzraikov)[<img alt="sipacate" src="https://avatars.githubusercontent.com/u/1827394?v=3&s=117" width="117">](https://github.com/sipacate)

[<img alt="dmccuskey" src="https://avatars.githubusercontent.com/u/933841?v=3&s=117" width="117">](https://github.com/dmccuskey)[<img alt="getsetbro" src="https://avatars.githubusercontent.com/u/442793?v=3&s=117" width="117">](https://github.com/getsetbro)[<img alt="tailsu" src="https://avatars.githubusercontent.com/u/730130?v=3&s=117" width="117">](https://github.com/tailsu)[<img alt="burkeholland" src="https://avatars.githubusercontent.com/u/686963?v=3&s=117" width="117">](https://github.com/burkeholland)[<img alt="jbristowe" src="https://avatars.githubusercontent.com/u/71493?v=3&s=117" width="117">](https://github.com/jbristowe)[<img alt="Lampei" src="https://avatars.githubusercontent.com/u/104018?v=3&s=117" width="117">](https://github.com/Lampei)

[<img alt="PanayotCankov" src="https://avatars.githubusercontent.com/u/5919275?v=3&s=117" width="117">](https://github.com/PanayotCankov)[<img alt="hshristov" src="https://avatars.githubusercontent.com/u/5966717?v=3&s=117" width="117">](https://github.com/hshristov)[<img alt="jlooper" src="https://avatars.githubusercontent.com/u/1450004?v=3&s=117" width="117">](https://github.com/jlooper)[<img alt="TsvetanMilanov" src="https://avatars.githubusercontent.com/u/10463529?v=3&s=117" width="117">](https://github.com/TsvetanMilanov)[<img alt="fritzvd" src="https://avatars.githubusercontent.com/u/160328?v=3&s=117" width="117">](https://github.com/fritzvd)[<img alt="FrancoisCamus" src="https://avatars.githubusercontent.com/u/7439901?v=3&s=117" width="117">](https://github.com/FrancoisCamus)

[<img alt="AntonDobrev" src="https://avatars.githubusercontent.com/u/3618710?v=3&s=117" width="117">](https://github.com/AntonDobrev)[<img alt="ejsuncy" src="https://avatars.githubusercontent.com/u/5944767?v=3&s=117" width="117">](https://github.com/ejsuncy)[<img alt="EvanWieland" src="https://avatars.githubusercontent.com/u/7815990?v=3&s=117" width="117">](https://github.com/EvanWieland)[<img alt="alexziskind1" src="https://avatars.githubusercontent.com/u/1638579?v=3&s=117" width="117">](https://github.com/alexziskind1)[<img alt="gabesumner" src="https://avatars.githubusercontent.com/u/377569?v=3&s=117" width="117">](https://github.com/gabesumner)[<img alt="n3wc" src="https://avatars.githubusercontent.com/u/1139568?v=3&s=117" width="117">](https://github.com/n3wc)

[<img alt="joshgking" src="https://avatars.githubusercontent.com/u/3820857?v=3&s=117" width="117">](https://github.com/joshgking)[<img alt="trevordowdle" src="https://avatars.githubusercontent.com/u/4210581?v=3&s=117" width="117">](https://github.com/trevordowdle)[<img alt="slavchev" src="https://avatars.githubusercontent.com/u/3962815?v=3&s=117" width="117">](https://github.com/slavchev)[<img alt="Pip3r4o" src="https://avatars.githubusercontent.com/u/10464986?v=3&s=117" width="117">](https://github.com/Pip3r4o)[<img alt="simmstein" src="https://avatars.githubusercontent.com/u/520175?v=3&s=117" width="117">](https://github.com/simmstein)[<img alt="toddanglin" src="https://avatars.githubusercontent.com/u/647319?v=3&s=117" width="117">](https://github.com/toddanglin)

[<img alt="e2l3n" src="https://avatars.githubusercontent.com/u/2971483?v=3&s=117" width="117">](https://github.com/e2l3n)[<img alt="alejonext" src="https://avatars.githubusercontent.com/u/1652887?v=3&s=117" width="117">](https://github.com/alejonext)[<img alt="VladimirAmiorkov" src="https://avatars.githubusercontent.com/u/4989411?v=3&s=117" width="117">](https://github.com/VladimirAmiorkov)[<img alt="williamho" src="https://avatars.githubusercontent.com/u/1883086?v=3&s=117" width="117">](https://github.com/williamho)[<img alt="peterennis" src="https://avatars.githubusercontent.com/u/140737?v=3&s=117" width="117">](https://github.com/peterennis)[<img alt="saiberz" src="https://avatars.githubusercontent.com/u/1022999?v=3&s=117" width="117">](https://github.com/saiberz)

[<img alt="svalchinov" src="https://avatars.githubusercontent.com/u/3678622?v=3&s=117" width="117">](https://github.com/svalchinov)[<img alt="nemephx" src="https://avatars.githubusercontent.com/u/12735072?v=3&s=117" width="117">](https://github.com/nemephx)

<!-- Note: The table above get generated with the following commands -->
<!-- npm install -g githubcontrib -->
<!-- githubcontrib --owner NativeScript --repo docs --cols 6 --sortOrder desc | pbcopy -->
