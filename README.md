# actions-playground

github actions playground

## context

https://docs.github.com/ja/actions/learn-github-actions/contexts#example-printing-context-information-to-the-log

https://github.com/marketplace/actions/dump-context

## when PR base branch changed

When it first set to others, the scenario not start build is right.
I expected when the base branch edit to trigger it.
It was not what I expected.
It seens synchronize not related to base branch changes.

Well, if I close and open again, the reopened event works.
