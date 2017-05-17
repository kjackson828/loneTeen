# loneTeen
public boolean loneTeen(int a, int b) {
  boolean aIsTeen = (a >= 13 && a <= 19);
  boolean bIsTeen = (b >= 13 && b <= 19);
 
 if ((aIsTeen && !bIsTeen) || (!aIsTeen && bIsTeen)){
   return true;
 }
 return false;
}
