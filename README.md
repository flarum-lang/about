# Flarum Lang
We all love our Flarum and its vastly existing ecosystem. One part of that is the many different language packs that are available. One of the significant challenges of an Open Source project is ensuring longevity. As of right now, language packs are tied to single persons (and their respective repositories). If one of those remarkable people maintaining their language pack becomes unavailable, this means the repository changes. Therefore all users of this language pack need to change something as well.

In consequence, the Flarum-lang (https://github.com/flarum-lang) initiative has been launched by the Flarum project. What's the objective? Hosting all language packs on this official repository so that they are available for all end-users under a consistent package even if, at some stage, the contributors may change.

Where can I get more information? https://discuss.flarum.org/d/27519-the-flarum-language-project

# FAQ.
## Want to use a language pack?
Installing language packs is identical to installing an extension. You will be using composer to download and install the package to your Flarum installation. You can find detailed instructions on the readme file of every language pack. Being hosted in flarum-lang means, though, that there is a uniform way on how to get a new language pack: `composer require flarum-lang/french:*`

You can replace `french` with every other available repository that has a compatible package released. For details once again, I recommend reading the readme of the specific language pack.

## Interested in translating yourself?
We love to see the ecosystem of Flarum language packs grow. We are convinced that with flarum-lang, we can ensure the longevity of those language packs and the best availability to users. This is why we are activly searching for new language pack maintainers to join the project.

### I am interested in joining and am currently maintaining a language pack in my own repository
Joining as a current maintainer of a language pack is pretty straightforward. Due to technical limitations, the easiest way is to let us (either on discuss or as an issue to this repository) know about your interest and then transfer the current repository to luceos. He then can move it to the flarum-lang organization. This keeps all history and issues alive. You will then get access to your language pack within the flarum-lang organization. We can discuss the details in person with you as soon as we know you are interested.

### I am interested in creating a new language pack
We are happy to see the availability of more and more language packs. If there is none available for your language, feel free to get in touch with us (either on discuss or as an issue to this repository), so we can discuss how you start. In addition, there is a great tool called Weblate (https://weblate.rob006.net/languages/) by rob006, making it possible for people not as familiar with GIT and code to start translating right away as well.

You can learn more about creating a new or joining your existing language pack in our official discussion: https://discuss.flarum.org/d/27519-the-flarum-language-project.
