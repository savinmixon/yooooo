public interface IPostsRepository
{
    void Save(Post mypost);
    Post Get(int id);
    PaginatedResult<Post> List(int skip,int pageSize);
    PaginatedResult<Post> SearchByTitle(string title,int skip,int pageSize);
}
