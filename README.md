using System;

namespace MyApplication
{ }
class Article
{
string metal;
string color;
int value;

static void Main(string[] args)
{
Article chain = new Article();
chain.metal = "gold";
chain.color = "golden";
chain.value = 45000;

Article paper = new Article();
paper.metal = "woodplup";
paper.color = "white";
paper.value = 20;

Console.WriteLine(chain.metal);
Console.WriteLine(chain.color);
Console.WriteLine(chain.value);
Console.WriteLine(paper.metal);
Console.WriteLine(paper.color);
Console.WriteLine(paper.value);
}
}
