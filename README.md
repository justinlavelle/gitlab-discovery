# GitLab Discovery
<p>
GitLab Discovery is a standalone and continuous development app for GitLab built with [Electron](https://electron.atom.io/), [Vue.js](https://github.com/vuejs/vue/) and [NUIverse](https://gitlab.com/nuinalp/nuiverse) and licensed by the BSD 3-clause license. We aim to create an amazing cross-platform desktop client to facilitate development and collaboration with GitLab services.
<p>

<p>
  <a href="https://www.patreon.com/nuinalp" target="_blank">
    <img src="https://c5.patreon.com/external/logo/become_a_patron_button.png" alt="Become a Patreon">
  </a>
</p>

<img src="homescreen.png" style="margin:auto; display:block; width:1000px;"/>

# Introduction

<p>
We developed this app initially to make our team work easier, but we thought it would be cool to share with the community and everyone who works with GitLab. We strive to create an interface as close as possible to the design language created by GitLab by adapting our NUIverse framework.
</p>

<h2>Why?</h2>

- Create seamless and seamless integration with GitLab resources
- Offer a better experience for the company's clients
- Offer features that GitHub Desktop does not offer
- Because GitHub Desktop was built for GitHub not for GitLab
- Offer more convenience and experience (I know how to work with Git, however I do not love working with terminals, so just as I do there are other people with the same opinion)
- Why is it right, the app is being built to help the community and to those who use the service, so in my view it is correct you install, log in and use. Do not have to reconfigure the App from a competing service to offer a better experience while interacting with the service
- Respect UX! The Ux of GitLab was designed for them, their users are familiar, so the App aims to do this too, be as faithful as possible to the ux of the platform.
- Bring more users, although I do not work for them, I know that when you offer a good allied service to a decent desktop client you can get more users, and regardless of whether new users know or do not like terminal can interfere in the choice of service
- Features and more features - My idea is to create a multiplatform App, so I want it to be in Windows, Linux and MacOS, so I would like the App to be as complete as possible so that it

<h2>Where do I get this?</h2>

<p>For now GitLab Discovery is not yet ready to be used by other people, however you can download the source code and compile yourself, initially it was project only to work in Windows.</p>

<strong>Note: To use the Direct Source App you need to do the following:</strong>

1- Create an access [token](https://gitlab.com/profile/personal_access_tokens) at with all scopes <br>
2- Create config.js in src /
``` 
export default{ 
  username: 'your_username', 
  token: 'Your_token', 
  name_user_with_space: 'Your_name' 
} 
```

3- Create projects file in src /
``` 
{"lastProject":[],"projects":[]} 
```
4 - npm install and npm run serve: electron

# License

[BSD Clause 3](LICENSE.md)

Copyright (c) 2018 The Nuinalp Authors. All rights reserved.<br>
Use of this source code is governed by a BSD-style license that can be found in the LICENSE file.