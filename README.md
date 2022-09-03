# LeetCode
DSA Sheet practice section
#Next permutation code
sort(nums.begin(),nums.end());
  do{
      ans.push_back(nums);
  }while(next_permutation(nums.begin(),nums.end()));
  return ans;
