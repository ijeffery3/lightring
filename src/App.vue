<template>
  <div class="app-container">
    <header class="header">
      <div class="logo-area">
        <!-- Logo Icon -->
        <div class="ring-icon"></div>
        <h1>LightRing</h1>
      </div>
    </header>

    <main class="content">
      <div class="paper">
        <h2>Privacy Policy</h2>
        <p class="date">Last updated: October 27, 2023</p>

        <section>
          <h3>1. Introduction</h3>
          <p>
            Welcome to <strong>LightRing</strong> ("we," "our," or "us"). We respect your privacy and are committed to protecting it through our compliance with this policy.
          </p>
          <p>
            This Privacy Policy describes Our policies and procedures on the collection, use, and disclosure of Your information when You use the Application and tells You about Your privacy rights and how the law protects You.
          </p>
        </section>

        <section>
          <h3>2. Information We Collect</h3>
          <p>We may collect and use the following types of information for the purposes of improving our services:</p>
          <ul>
            <li><strong>Device Information:</strong> We may collect information about your mobile device, including but not limited to the device model, operating system version, and unique device identifiers.</li>
            <li><strong>Usage Data:</strong> We may collect data on how you access and use the application (e.g., features used, time spent on the app).</li>
            <li><strong>Camera and Photo Library:</strong> LightRing requires access to your device's camera and photo library to provide its core lighting and effect features. <strong>Please note:</strong> We do not upload your personal photos or videos to our servers. All image processing is performed locally on your device.</li>
          </ul>
        </section>

        <section>
          <h3>3. Data Security</h3>
          <p>
            The security of Your Personal Data is important to Us, but remember that no method of transmission over the Internet, or method of electronic storage is 100% secure. While We strive to use commercially acceptable means to protect Your Personal Data, We cannot guarantee its absolute security.
          </p>
        </section>

        <section>
          <h3>4. Third-Party Services</h3>
          <p>
            Our Service may contain links to other websites that are not operated by Us. If You click on a third-party link, You will be directed to that third party's site. We strongly advise You to review the Privacy Policy of every site You visit.
          </p>
          <p>
            We have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party sites or services.
          </p>
        </section>

        <section>
          <h3>5. Children's Privacy</h3>
          <p>
            Our Service does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from anyone under the age of 13. If You are a parent or guardian and You are aware that Your child has provided Us with Personal Data, please contact Us.
          </p>
        </section>

        <section>
          <h3>6. Changes to this Privacy Policy</h3>
          <p>
            We may update Our Privacy Policy from time to time. We will notify You of any changes by posting the new Privacy Policy on this page. You are advised to review this Privacy Policy periodically for any changes.
          </p>
        </section>

        <section>
          <h3>7. Contact Us</h3>
          <p>If you have any questions about this Privacy Policy, You can contact us:</p>
          <p>By email: <a href="mailto:cosyjfwan@gmail.com">cosyjfwan@gmail.com</a></p>
        </section>
      </div>
    </main>

    <footer class="footer">
      <p>&copy; {{ new Date().getFullYear() }} LightRing Team. All rights reserved.</p>
    </footer>
  </div>
</template>

<script setup>
// Static content, no complex logic needed
</script>

<style>
/* Global Reset */
body {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  background-color: #f5f7fa;
  color: #333;
  line-height: 1.6;
}

/* Layout Container */
.app-container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

/* Header */
.header {
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  padding: 1rem 0;
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo-area {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 20px;
  display: flex;
  align-items: center;
  gap: 12px;
}

.ring-icon {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  border: 4px solid #6366f1; /* Brand Color: Indigo */
  box-shadow: 0 0 10px rgba(99, 102, 241, 0.5);
}

.header h1 {
  margin: 0;
  font-size: 1.5rem;
  color: #1f2937;
  font-weight: 700;
}

/* Main Content */
.content {
  flex: 1;
  padding: 40px 20px;
  width: 100%;
  box-sizing: border-box;
}

.paper {
  max-width: 800px;
  margin: 0 auto;
  background: #fff;
  padding: 40px;
  border-radius: 12px;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
}

h2 {
  font-size: 2rem;
  margin-top: 0;
  color: #111827;
  border-bottom: 2px solid #f3f4f6;
  padding-bottom: 10px;
}

.date {
  color: #6b7280;
  font-size: 0.9rem;
  margin-bottom: 30px;
  font-style: italic;
}

section {
  margin-bottom: 30px;
}

h3 {
  color: #374151;
  font-size: 1.25rem;
  margin-bottom: 10px;
  font-weight: 600;
}

p, ul {
  color: #4b5563;
  margin-bottom: 10px;
}

ul {
  padding-left: 20px;
}

li {
  margin-bottom: 8px;
}

a {
  color: #6366f1;
  text-decoration: none;
  font-weight: 500;
}

a:hover {
  text-decoration: underline;
}

/* Footer */
.footer {
  text-align: center;
  padding: 20px;
  color: #9ca3af;
  font-size: 0.875rem;
  border-top: 1px solid #e5e7eb;
  background-color: #fff;
}

/* Mobile Responsiveness */
@media (max-width: 600px) {
  .paper {
    padding: 20px 20px;
  }
  
  h2 {
    font-size: 1.5rem;
  }
}
</style>