# noted

Just a quick filter in your Rails projects for notes tasked to you. Looks through your notes
for your github username (@twitter style) and dutifully reports it back to you.

## install

`gem install noted`

## usage

So, like this:

    def awesome?
        everyone_else?
        # TODO: shit, I should make sure I'm awesome, too   - @holman
    end

...lets you then do something like this:

    noted
    => app/models/awesomator.rb:
    =>  * [ 94] [TODO] shit, I should make sure I'm awesome, too    - @holman

## about

[@holman](http://twitter.com/holman) did this.