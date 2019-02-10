---
title: Submit a Show
---

Use the form below to submit a show. 

<form method="POST" name="Show" data-netlify="true">

    <div class="field">
        <label for="eventTitle" class="label">Event title</label>
        <div class="control">
            <input class="input" type="text" name="eventTitle" id="eventTitle">
        </div>
    </div>
    <div class="field">
        <label for="eventPerformers" class="label">Performers</label>
        <div class="control">
            <input class="input" type="text" name="eventPerformers" id="eventPerformers">
        </div>
    </div>
    <div class="field">
        <label for="eventDate" class="label">Date</label>
        <div class="control">
            <input class="input" type="text" name="eventDate" id="eventDate" placeholder="2019-02-15">
        </div>
    </div>
    <div class="field">
        <label for="eventVenue" class="label">Venue</label>
        <div class="control">
            <input class="input" type="text" name="eventVenue" id="eventVenue" placeholder="Wacky Warehouse">
        </div>
    </div>
    <div class="field">
        <label for="eventCost" class="label">Cost</label>
        <div class="control">
            <input class="input" type="text" name="eventCost" id="eventCost" placeholder="$5">
        </div>
    </div>
    <div class="field">
        <label for="eventImage" class="label">Flyer URL</label>
        <div class="control">
            <input class="input" type="text" name="eventImage" id="eventImage" placeholder="https://">
        </div>
        <p class="help">You can upload images to <a href="https://imgur.com">Imgur</a> if you don't have a URL for your flyer.</p>
    </div>
    <div class="field">
        <label for="eventAuthor" class="label">Your name</label>
        <div class="control">
            <input class="input" type="text" name="eventAuthor" id="eventAuthor">
        </div>
    </div>
    <div class="field">
        <label for="eventDescription" class="label">Description</label>
        <div class="control">
            <textarea name="eventDescription" id="eventDescription" rows="4" class="textarea"></textarea>
        </div>
    </div>

    <div class="field">
        <div data-netlify-recaptcha="true" class="control"></div>
    </div>
    <div class="field is-grouped is-grouped-centered">
        <div class="control">
            <input type="submit" value="Submit" class="button is-link">
        </div>
    </div>
</form>