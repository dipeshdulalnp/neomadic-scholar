+++
author = "Anonymous"
title = "Contact Us"
date = "2026-03-05"
description = "Contact Us with a method of your choice - office visits, emails, phone calls, WhatsApp messages, you name it!"
+++
<style>
  .contact-section-wrapper {
    display: flex;
    flex-wrap: wrap;
    gap: 24px;
    align-items: stretch;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #333;
    width: 100%;
    margin: 20px 0;
    box-sizing: border-box;
  }

  .contact-map-col,
  .contact-info-col {
    flex: 1 1 300px;
    width: 50%;
    min-width: 280px;
    box-sizing: border-box;
  }

  /* Left Side: Map Container */
  .contact-map-col {
    position: relative;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    min-height: 380px;
  }

  .contact-map-col iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100% !important;
    height: 100% !important;
    border: 0;
  }

  /* Right Side: Details Container */
  .contact-info-col {
    background: #ffffff;
    padding: 24px;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .contact-info-col h2 {
    font-size: 1.4rem;
    color: #1a202c;
    margin-top: 0;
    margin-bottom: 8px;
  }

  .contact-info-col .subtext {
    color: #666;
    margin-bottom: 20px;
    font-size: 0.95rem;
  }

  .contact-detail-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .contact-detail-item {
    display: flex;
    align-items: flex-start;
    padding: 12px 0;
    border-bottom: 1px solid #edf2f7;
  }

  .contact-detail-item:last-child {
    border-bottom: none;
  }

  .contact-detail-icon {
    font-size: 1.25rem;
    margin-right: 12px;
  }

  .contact-detail-text h4 {
    font-size: 0.85rem;
    color: #2d3748;
    margin: 0 0 2px 0;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  .contact-detail-text p,
  .contact-detail-text a {
    color: #4a5568;
    text-decoration: none;
    font-size: 0.95rem;
    margin: 0;
  }

  .contact-detail-text a {
    color: #7212aa;
  }

  .contact-detail-text a:hover {
    text-decoration: underline;
  }

  .consultation-notice {
    margin-top: 20px;
    background-color: #f9ebff;
    border-left: 4px solid #9431ce;
    padding: 12px 16px;
    border-radius: 4px;
  }

  .consultation-notice p {
    margin: 0;
    font-size: 0.9rem;
    color: #2d3748;
  }
</style>

<div class="contact-section-wrapper">
  <!-- Left Side: Map -->
  <div class="contact-map-col">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1486.5074233367875!2d85.33487606069856!3d27.687080399739585!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39eb1900495ec993%3A0x633f4629ab7469f6!2sNeoMADiC%20Scholar%20Education%20Consultancy%20Pvt.%20Ltd.!5e1!3m2!1sen!2snp!4v1789801132104!5m2!1sen!2snp" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
  </div>

  <!-- Right Side: Contact Details -->
  <div class="contact-info-col">
    <h2>You can contact us via:</h2>
    <p class="subtext">Reach out to us through any of the channels below.</p>
    <ul class="contact-detail-list">
      <li class="contact-detail-item">
        <span class="contact-detail-icon">📞</span>
        <div class="contact-detail-text">
          <h4>Phone</h4>
          <p>
            <a href="tel:+9779847558458">984-7558458</a>, 
            <a href="tel:+977015925776">01-5925776</a>
          </p>
        </div>
      </li>
      <li class="contact-detail-item">
        <span class="contact-detail-icon">✉️</span>
        <div class="contact-detail-text">
          <h4>Email</h4>
          <p><a href="mailto:info@neomadic.com.np">info@neomadic.com.np</a></p>
        </div>
      </li>
      <li class="contact-detail-item">
        <span class="contact-detail-icon">🌐</span>
        <div class="contact-detail-text">
          <h4>Facebook</h4>
          <p><a href="https://facebook.com/neomadicscholar.edu" target="_blank" rel="noopener noreferrer">Visit our Facebook Page</a></p>
        </div>
      </li>
    </ul>
    <div class="consultation-notice">
      <p>For face-to-face consultation, please visit us at our office located at <strong>New Baneshwor, Kathmandu</strong>.</p>
    </div>
  </div>
</div>