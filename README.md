# email-signature
In this tutorial, [Solodev](https://www.solodev.com/) explains the necessary HTML to create a unique email signature that you can customize to fit the needs of your organization. 

## Tutorial

For detailed instructions, view Solodev's [Creating a HTML Email Signature](https://www.solodev.com/blog/web-design/creating-a-html-email-signature.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/kjrf3p18/).

## HTML

Use the following HTML for the tutorial:

```
  <table border="0" cellpadding="0" cellspacing="0" width="500">
    <tbody>
      <tr>
        <td border="0" cellpadding="0" cellspacing="0" height="38" width="222">
          <img src="https://www.solodev.com/assets/email-signature/solodev-logo.jpg" alt="Solodev Icon">
        </td>
      </tr>
      <tr>
        <td height="64" style="font-family:Helvetica, Arial, sans-serif; font-size:18px; font-style:bold;">
          <strong>John Smith</strong>
          <br>
          <em style="font-size:17px; font-weight:400;">Software Engineer</em>
        </td>
      </tr>
      <tr>
        <td height="58" style="font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4e;">
          800 N. Magnolia Ave, Suite 1400 | Orlando, Fl 32803
          <br> Office 407.898.1961
        </td>
      </tr>
      <tr>
        <td class="hover" height="60" style="font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#d0292d;">
          <a href="mailto:john.smith@solodev.com" onMouseOver="this.style.color='#71080a'" onMouseOut="this.style.color='#d0292d'" style="color:#d0292d; ">john.smith@solodev.com</a>
          <br>
          <a href="https://www.solodev.com/" onMouseOver="this.style.color='#71080a'" onMouseOut="this.style.color='#d0292d'" target="_blank" style="color:#d0292d;">solodev.com</a>
        </td>
      </tr>
      <tr>
        <td height="55">
          <a href="https://www.facebook.com/Solodev" target="_blank"><img src="https://www.solodev.com/assets/email-signature/facebook-email-icon.jpg" alt="Facebook Icon"></a>
          <a href="https://www.linkedin.com/company/solodev" target="_blank"><img src="https://www.solodev.com/assets/email-signature/linkedin-email-icon.jpg" alt="LinkedIn Icon"></a>
          <a href="https://twitter.com/solodev" target="_blank"><img src="https://www.solodev.com/assets/email-signature/twitter-email-icon.jpg" alt="Twitter Icon"></a>
        </td>
      </tr>
      <tr>
        <td height="70">
          <small style="font-family:Helvetica, Arial, sans-serif; font-size:10px; color:#4d4d4e;">Confidentiality Notice: This e-mail message, including any attachments, is for the sole use of the intended recipient(s) and may contain confidential and privileged information. Any unauthorized review, use, disclosure or distribution of this information is prohibited, and may be punishable by law. If this was sent to you in error, please notify the sender by reply e-mail and destroy all copies of the original message. Please consider the environment before printing this e-mail.</small>
        </td>
      </tr>
    </tbody>
  </table>
```

## CSS

No additional CSS is needed


## External Includes

No external files are needed

