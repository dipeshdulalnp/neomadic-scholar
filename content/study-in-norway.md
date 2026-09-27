+++
author = "Anonymous"
title = "Study in Norway"
date = "2026-03-05"
description = "Get counselling from our counselor who is a graduate from Norway."
+++


<div class="contact-form-wrapper">
  <iframe id="hidden_iframe" name="hidden_iframe" onload="if(typeof submitted !== 'undefined' && submitted){showSuccess();}" style="display: none;"></iframe>
  <form action="https://docs.google.com/forms/d/e/1FAIpQLSfRIGQ7lUib_43TnbPWGHYJd6LPJLSBn5sPVpf3TvtQJturcw/formResponse" id="custom-contact-form" method="POST" onsubmit="return validateAndSubmit();" target="hidden_iframe">
    <div class="form-group">
      <label>Full  Name of Student</label>
      <textarea name="entry.983114800" placeholder="Full  Name of Student" required="" rows="8"></textarea>
    </div>
    <div class="form-group">
      <label>Latest Academic Qualification</label>
      <textarea name="entry.2097402162" placeholder="Latest Academic Qualification" required="" rows="8"></textarea>
    </div>
    <div class="form-group">
      <label>Intended Study Programme in Norway</label>
      <textarea name="entry.903091946" placeholder="Intended Study Programme in Norway" required="" rows="8"></textarea>
    </div>
    <div class="form-group">
      <label>Do you have valid score of English language test?</label>
      <textarea name="entry.1936835106" placeholder="Do you have valid score of English language test?" required="" rows="8"></textarea>
    </div>
    <div class="form-group">
      <label>If you have valid score of English language test, please mention the score. (For example: IELTS Academic - 6.5, No Score, TOEFL iBT - 96)</label>
      <textarea name="entry.444765763" placeholder="If you have valid score of English language test, please mention the score. (For example: IELTS Academic - 6.5, No Score, TOEFL iBT - 96)" required="" rows="8"></textarea>
    </div>
    <div class="form-group">
      <label>Contact Number </label>
      <input name="entry.978837109" placeholder="Contact Number " required="" type="text" />
    </div>
    <div class="button-container">
      <button class="contact-form-button-submit" type="submit">Submit</button>
    </div>
  </form>
</div>

<style>
  .contact-form-wrapper { width: 100%; max-width: 700px; margin: 20px auto; padding: 30px; background: #fff; border: 1px solid #eee; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); box-sizing: border-box; }
  .form-group { margin-bottom: 20px; }
  .form-group label { display: block; margin-bottom: 8px; font-weight: bold; color: #333; font-size: 1rem; }
  .form-group input, .form-group textarea { width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 6px; box-sizing: border-box; font-size: 16px; background: #fff; color: #000; }
  .form-group input:focus, .form-group textarea:focus { border-color: #555555; outline: none; }
  .button-container { text-align: center; margin-top: 25px; }
  .contact-form-button-submit { background: #555555; color: #fff; border: none; padding: 12px 60px; font-size: 1.1rem; font-weight: bold; border-radius: 50px; cursor: pointer; transition: 0.3s; }
  .contact-form-button-submit:hover { opacity: 0.8; transform: translateY(-2px); }
  .blog-pager, .paging-control { display: none !important; }
</style>

<script>
  var submitted = false;
  function validateAndSubmit() {
    submitted = true;
    const btn = document.querySelector('.contact-form-button-submit');
    btn.disabled = true;
    btn.innerHTML = 'submitting the form ...';
    return true;
  }
  function showSuccess() {
    if (submitted) {
      document.getElementById('custom-contact-form').innerHTML = `
        <div style="display: flex; justify-content: center; align-items: center; min-height: 250px; text-align: center;">
          <p style="color: #555555; font-size: 1.2rem; font-weight: bold;">Thank you for submitting the form. We will get back to as soon as possible.</p>
        </div>`;
      window.scrollTo({ top: document.querySelector('.contact-form-wrapper').offsetTop - 50, behavior: 'smooth' });
    }
  }
</script>