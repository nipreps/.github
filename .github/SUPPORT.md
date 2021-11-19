# Support

This document describes how to get help with *NiPreps*.
We want to start off by saying thank you for using *NiPreps*.
This project is a labor of love, and we appreciate all of the users that share the problems they encounter using our tools, catch bugs, make performance improvements, and help with documentation.
Every contribution is meaningful, so thank you for participating.
Here are a few guidelines that we ask you to follow so we can successfully address your issue.


## Before you start: the Code of Conduct

> 👉 **Note**: before participating in our community, please read our
> [code of conduct][coc].
> By interacting with this repository, organization, or community you agree to
> abide by its terms.

## You've encountered a problem

The *NiPreps* framework is built on experimental research software, so it is very likely that you will hit some snags before you get the ball rolling.
It's definitely not your fault, do not give up!

Before you go ahead and ask a question, we ask you to do some research on your end.
Chances are that someone has gon thorugh the same or a similar issue, and the response is recorded somewhere.
Where to check for answers (in order of priority):

  1. [NeuroStars][neurostars]: this is a forum for neuroscientists like StackOverflow for programmers.
  1. [Nipy Discourse][discourse]: this is a platform similar to NeuroStars, but we use it for public communication with the community and at the time of writing doesn't really have particular debugging information, but you can find interesting resources here.
  1. [*NiPreps* general documentation][nipreps]: here we provide some advice regarding how to run containers, how to set up [*TemplateFlow*][templateflow], etc.
  1. **The Project's documentation site**. Our projects usually have an FAQ (frequently asked questions) that are specific to the tool.
  1. **The Project's issue tracker at GitHub**. You'll easily find the issue tracker with the URL `https://github.com/nipreps/<project>/issues` (do not forget to replace `<project>` with the actual project name -- e.g., [`https://github.com/nipreps/fmriprep/issues`][fmriprep-issues])
  1. If you're still not sure where to begin, feel free to pop into [the Brainhack's mattermost][mattermost] and introduce yourself!
     You'll find some channels for particular tools (e.g., [*#fMRIPrep*][mattermost-fmriprep], [*#dMRIPrep*][mattermost-dmriprep], [*#MRIQC*][mattermost-mriqc]) where you can post your questions, although it is not guaranteed that it will be revised any time soon.

Please understand that we run this community on semi- or fully-volunteering basis, and sometimes our availability is very reduced.

## Asking quality questions

General questions should go to [NeuroStars][neurostars].
If you want to join our meetings or learn more about the community, you can head to [Nipy Discourse][discourse].
If you think neither of those is the right place, you are probably facing a bug - please then head to the project's GitHub discussions or the issue tracker (e.g., [*fMRIPrep* discussions][fmriprep-discussions] and [*fMRIPrep* issues][fmriprep-issues]).

Help us help you!
Spend time framing questions and add links and resources.
Spending the extra time up front can help save everyone time in the long run.
Here are some tips:

*   [Validate your BIDS dataset][validator]
*   [Talk to a duck][rubberduck]!
*   Don’t fall for the [XY problem][xy]
*   Try to define what you need help with:
    *   Is there something in particular you want to do?
    *   What problem are you encountering and what steps have you taken to try
        and fix it?
    *   Is there a concept you don’t understand?
*   Make sure you provide us with sufficient level of detail to understand the issue and, if possible, recreate it in our own settings.
    To do so, it is important that you provide details such as the exact command line you were running, the full log that the tool generated, data (if you can share them), visual reports, etc. An guide of potential questions is found [here](https://github.com/nipreps/fmriprep/issues/new?assignees=&labels=bug&template=bug_report.yml).
*   The more time you put into asking your question, the better we can help you

!!! note
    Guidelines derived from [Titus Wormer][author]'s [`SUPPORT.md` file for RemarkJS][source]

<!-- Definitions -->

[license]: https://creativecommons.org/licenses/by/4.0/

[author]: https://wooorm.com

[coc]: https://www.nipreps.org/community/CODE_OF_CONDUCT/

[rubberduck]: https://rubberduckdebugging.com

[xy]: https://meta.stackexchange.com/questions/66377/what-is-the-xy-problem/66378#66378

[cs]: https://codesandbox.io

[contributing]: contributing.md

[neurostars]: https://neurostars.org

[discourse]: https://nipy.discourse.group/c/nipreps/9

[nipreps]: https://nipreps.org

[templateflow]: https://templateflow.org

[fmriprep-issues]: https://github.com/nipreps/fmriprep/issues

[fmriprep-discussions]: https://github.com/nipreps/fmriprep/discussions

[validator]: http://bids-standard.github.io/bids-validator/

[source]: https://github.com/remarkjs/.github/blob/9858b4b693d61337b6d5ab37d36304d2a4b0bf33/support.md

[mattermost]: https://mattermost.brainhack.org/brainhack/

[mattermost-dmriprep]: https://mattermost.brainhack.org/brainhack/channels/dmriprep

[mattermost-fmriprep]: https://mattermost.brainhack.org/brainhack/channels/fmriprep

[mattermost-mriqc]: https://mattermost.brainhack.org/brainhack/channels/MRIQC
