--- 
permalink: /preview-components/sign-in-form.html
layout: iframed 
title: Sign-in-form.html
---
<form class="form">
    <fieldset>
        <legend class="drop_text">Sign in</legend>
        <span>or
            <a href="javascript:void(0);">create an account</a>
        </span>

        <label for="username">Username or email address</label>
        <input id="username" name="username" type="text" autocapitalize="off" autocorrect="off">

        <label for="password">Password</label>
        <input id="password" name="password" type="password">
        <p class="form-note">
            <a title="Show password" href="javascript:void(0);" class="show_password" aria-controls="password-sign-in">Show password</a>
        </p>

        <input type="submit" value="Sign in">
        <p>
            <a href="javascript:void(0);" title="Forgot username">
                Forgot username?</a>
        </p>
        <p>
            <a href="javascript:void(0);" title="Forgot password">
                Forgot password?</a>
        </p>
    </fieldset>
</form>