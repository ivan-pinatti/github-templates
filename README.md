# Github Markdown Template Files for Bugs, New Features, Pull Requests, Questions, etc...

![GitHub issues](https://img.shields.io/github/issues-raw/ivan-pinatti/github-templates?logo=Github&style=for-the-badge)
![GitHub Sponsors](https://img.shields.io/github/sponsors/ivan-pinatti?logo=Github&style=for-the-badge)

The files in this repo are markdown templates for Github.\
You can use them to configure a already created repository and improved its usability.

If you are trying to template Github repos for your organization, please check the official documentation at https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository

---
# Usage

On your shell follow the steps below.

Define your repo folder
```shell
MY_TARGET_REPO_FOLDER=/home/${USER}/workspace/github-template
```

Create the **.github folder** if it doesn't exist yet
```shell
mkdir --parents ${MY_TARGET_REPO_FOLDER}/.github/ISSUE_TEMPLATE
```

Copy the markdown template files to the newly created .github folder
```shell
find */ -iname '*.md' -exec cp {} ${MY_TARGET_REPO_FOLDER}/.github/ISSUE_TEMPLATE \;
```

---
# License
[![license](https://img.shields.io/github/license/ivan-pinatti/docker-torrent-box?style=plastic)](https://github.com/ivan-pinatti/docker-torrent-box/blob/master/LICENSE)

See [LICENSE](LICENSE) for full details.

> ```THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.```

---
# Contribute / Donate
If you are using the code, entirelly or partially, forking the project, or getting inspired by it, consider buying me a coffee or maybe a beer, I would really appreciate it :smiley:

<a href="https://www.buymeacoffee.com/ivan.pinatti" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

