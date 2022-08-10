# devops-netology_7.6   
1. 
1.1.  
resource - https://github.com/hashicorp/terraform-provider-aws/blob/main/internal/provider/provider.go#L916-L2118    
data_source - https://github.com/hashicorp/terraform-provider-aws/blob/main/internal/provider/provider.go#L413-L914  

1.2.  
- https://github.com/hashicorp/terraform-provider-aws/blob/main/internal/service/sqs/queue.go#L87  
- вместе с расширением .fifi 80 символов (re = regexp.MustCompile(`^[a-zA-Z0-9_-]{1,75}\.fifo$`))  
- (`^[a-zA-Z0-9_-]{1,75}\.fifo$`) или (`^[a-zA-Z0-9_-]{1,80}$`)  
