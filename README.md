# github-local-remote-0.1.1-fn main() {
  let res = github_local_remote::stat(".").unwrap();
  println!("result {:?}", res);
