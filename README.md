A01Q5
=====
void del(struct node *head)
{
struct node*temp=head;
struct node*ptemp=temp->next;
while(temp)
{
temp=ptemp;
ptemp=ptemp->next;
free(temp);
}
}
