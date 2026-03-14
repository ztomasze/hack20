# Process

How I intended to work on this project.

## Issues

I tend to build a lot of separate design notes with discussion of tradeoffs and ultimate decisions made.  I plan to use GitHub Issues this time around, so that discussion can be linked to corresponding changes and versions as things evolve.

* Each rule section or subsection should have a corresponding issue of design documentation.

## Clean commits

To support issue linking, each `docs/` commit should touch a single rule at a time.

> I was originally going to use tags and a `CHANGELOG.md` following [common-changelog](https://common-changelog.org/) format. The version would change each time there was a push (and thus a publish) of `docs/` changes.
>
> * MAJOR = edition change
> * MINOR = rule change <!--(only additions or options after 1.0)-->
> * PATCH = corrections, style changes, etc.
> 
> However, this was quickly deemed too much unnecessary machinery for an unpublished solo work. I can revisit that if we ever get to 1.0.
