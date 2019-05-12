# Simple Partials Lab

## Objectives

1. Use the `render` method to render partials
2. Understand how the name of a partial turns into its filename
3. Practice rendering partials in a different folder

## Overview

Flatiron is building out a new system to keep track of students in its classes. You just joined the technical team and see that there's lots of repetition in the view layer of the code base. Use your new knowledge of partials to remove the duplication.

## Instructions

First, fork and clone the lab.

We've provided a seed file so you can have some data to play around with. Run `rake db:seed` to seed the database.

1. Remove the duplicated code in the `students/edit.html.erb` and `students/new.html.erb` files by making a partial called `students/_form.html.erb`.
2. Remove the duplicated code in the `classrooms/show.html.erb` and `students/show.html.erb` files by making a partial called `students/_student.html.erb`.

## Does this need an update?

Please open a [GitHub issue](https://github.com/learn-co-curriculum/phrg-simple-partials-lab/issues) or [pull-request](https://github.com/learn-co-curriculum/phrg-simple-partials-lab/pulls). Provide a detailed description that explains the issue you have found or the change you are proposing. Then "@" mention your instructor on the issue or pull-request, and send them a link via Connect.
