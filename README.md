# When start new project, need clone scss example schoolhouse.com clone from soundhouse.com.
sass/fontface.scss - define font family o day.
sass/variables.scss - define variable font scss here.
# Note when styling
# Not use !important when no need
# .left-addon input{padding-left: 30px;} minh viet scss, khong viet theo kieu nay, viet nhu sau:
.left-addon{
  input{
    padding-left: 30px;
    padding-right: 30px;
  }
}
# When use flex display, thay vi moi lan muon xai display: flex phai viet lai, thi viet 1 function trong mixin.scss, va khi nao can chi viec goi do ra. 
Example: 
@mixin flexbox() {
 display: -webkit-box;
 display: -moz-box;
 display: -ms-flexbox;
 display: -webkit-flex;
 display: flex;
}
.div{
    @include flexbox();
}

# Define color trong file variables.scss, va khi style trong 1_template.scss, 2_template.scss, color: $biencolor; 
