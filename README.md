resource "google_storage_bucket" "bucket" {
 count = 1
 name = "terraformbucket65d43202328"
 location = "europe-west2"
 storage_class = "REGIONAL"
}
