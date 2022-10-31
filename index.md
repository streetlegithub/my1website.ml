Testing testing... 123!

<div id="respond">  
  <h3>Leave a Comment</h3>  
<br>  
  <form action="commentLater.php" method="post" id="commentform">  
<br>  
    <label for="comment_author" class="required">Enter your name:</label>  
    <input type="text" name="comment_author" id="comment_author" value="" tabindex="1" required="required">  
  
    <br>  
    <label for="comment" class="required">  
<br>  
Enter your message</label>  
<br>  
    <textarea name="comment" id="comment" rows="10" tabindex="4"  required="required"></textarea>  
<br>  
    
    <input type="hidden" name="comment_post_ID" value="1" id="comment_post_ID" />  
    <input name="submit" type="submit" value="Submit comment" />  
  </form>  
</div>  
