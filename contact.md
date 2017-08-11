---
layout: contact
---
<div class="contact-container container-fluid">
    <div class="page-header">
        <h1>Contact Me</h1>
    </div>
    <form action="mailto:nickwang14@gmail.com" class="form-horizontal " method="post" role="form" enctype="text/plain">
        <div class="form-group">
            <label for="email" class="col-sm-2 control-label">E-mail</label>
            <div class="col-sm-4">
                <input type="email" class="form-control" id="email" name="email" placeholder="E-mail" required autofocus>
            </div>
        </div>
        <div class="form-group">
            <label for="name" class="col-sm-2 control-label">Name</label>
            <div class="col-sm-4">
                <input type="text" class="form-control" id="name" name="name" placeholder="Name" required>
            </div>
        </div>
        <div class="form-group">
            <label for="name" class="col-sm-2 control-label">Message</label>
            <div class="col-sm-5">
                <textarea id="message" name="message" class="form-control" placeholder="Your Message" rows="5" required></textarea>
            </div>
        </div>
        <div class="form-group">
            <div class="col-sm-offset-2 col-sm-6">
                <button type="submit" class="btn btn-primary">Poke</button>
            </div>
        </div>
    </form>
</div>