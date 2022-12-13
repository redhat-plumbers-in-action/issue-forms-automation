# Issue Forms Automation

[![GitHub Marketplace][market-status]][market]

[market]: https://github.com/marketplace/actions/advanced-issue-labeler
[market-status]: https://img.shields.io/badge/Marketplace-Advanced%20Issue%20Labeler-blue.svg?colorA=24292e&colorB=0366d6&style=flat&longCache=true&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAAM6wAADOsB5dZE0gAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAAERSURBVCiRhZG/SsMxFEZPfsVJ61jbxaF0cRQRcRJ9hlYn30IHN/+9iquDCOIsblIrOjqKgy5aKoJQj4O3EEtbPwhJbr6Te28CmdSKeqzeqr0YbfVIrTBKakvtOl5dtTkK+v4HfA9PEyBFCY9AGVgCBLaBp1jPAyfAJ/AAdIEG0dNAiyP7+K1qIfMdonZic6+WJoBJvQlvuwDqcXadUuqPA1NKAlexbRTAIMvMOCjTbMwl1LtI/6KWJ5Q6rT6Ht1MA58AX8Apcqqt5r2qhrgAXQC3CZ6i1+KMd9TRu3MvA3aH/fFPnBodb6oe6HM8+lYHrGdRXW8M9bMZtPXUji69lmf5Cmamq7quNLFZXD9Rq7v0Bpc1o/tp0fisAAAAASUVORK5CYII=

This repository is trying to demonstrate the power of [issue forms](https://github.blog/changelog/2021-06-23-issues-forms-beta-for-public-repositories/) and automation to provide better developer experience by labeling issues based on provided input.

This repository uses [@stefanbuck/github-issue-parser](https://github.com/stefanbuck/github-issue-parser) GitHub Action to parse issues generated based on issue forms, and output is passed to [@redhat-plumbers-in-action/advanced-issue-labeler](https://github.com/redhat-plumbers-in-action/advanced-issue-labeler) GitHub Action that is responsible for the labeling of the issues.
